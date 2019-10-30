node{  
 

  // 镜像中代码构建
  stage('Build'){    

    docker.image('buildbot:2.5.2').inside {
      //git credentialsId: 'git-credential', url: 'https://gitlab.com/bluvec/sw/controller.git'
      //sh 'go build'
      sh 'ls'
      sh 'cd ~'
      sh 'which go'
      sh 'mkdir workdir'
      sh 'cd workdir'
      sh 'ls'
    }
  }
}
