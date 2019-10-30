node{  
  
  stage('get Code') {
    git credentialsId: 'git-credential', url: 'https://gitlab.com/bluvec/sw/controller.git'
  }

  // 镜像中代码构建
  stage('Build'){    

    docker.image('golang:latest').inside {
      sh 'go version'
    }
  }
}
