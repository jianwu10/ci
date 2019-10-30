node{  
 

  // 镜像中代码构建
  stage('Build'){    

    //docker.image('buildbot:2.5.2').inside('-v $HOME/workdir:/home/buildbot/workdir -v $HOME/tools:/home/buildbot/tools') {
      //git credentialsId: 'git-credential', url: 'https://gitlab.com/bluvec/sw/controller.git'
      //sh 'go build'
      sh 'docker run -t --rm -v $HOME/workdir:/home/buildbot/workdir -v $HOME/tools:/home/buildbot/tools buildbot:2.5.2 /bin/bash'
      sh 'ls'
      sh 'cd ~'
      //sh 'which go'
      //sh 'mkdir workdir'
      //sh 'cd ~/workdir'
      sh 'ls'
      sh 'whoami'
    }
  //}
}
