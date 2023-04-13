pipeline {
  agent {
    docker { image 'httpd' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'mv test.html /var/www/html'
      }
    }
  }
}
