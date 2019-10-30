node{  
  
  stage('get Code') {
    git credentialsId: 'git-credential', url: 'https://gitlab.com/bluvec/sw/controller.git'
  }

  // 镜像中代码构建
  stage('Build'){    

    docker.image('buildbot:2.5.2').inside {
      sh 'npm version'
      sh 'ls'
      sh 'go build'
      sh 'cd ..'
      sh 'ls'
    }
  }
}
