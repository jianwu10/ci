node{  

  // 镜像中代码构建
  stage('Build'){    

    docker.image('golang:latest').inside {
      sh 'go version'
    }
  }
