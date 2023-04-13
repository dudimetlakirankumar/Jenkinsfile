pipeline {
  agent {
    docker { image 'httpd' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'cp source/*' '/var/www/html/'
      }
    }
  }
}
