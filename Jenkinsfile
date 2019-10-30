node{  
 

  // 镜像中代码构建
  stage('Build'){    

    docker.image('golang:latest').inside {
     // git credentialsId: 'git-credential', url: 'https://gitlab.com/bluvec/sw/controller.git'
      sh 'go build'
      sh 'ls'
      sh 'cd ~'
      sh 'ls'
    }
  }
}
