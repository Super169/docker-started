pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile'
    }
    
  }
  stages {
    stage('Get Source') {
      steps {
        git(branch: 'master', url: 'https://github.com/Super169/docker-started.git', poll: true)
      }
    }
  }
}