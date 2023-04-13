pipeline {
  agent {
    docker { image 'httpd' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'mv source/* /var/www/html'
      }
    }
  }
}
