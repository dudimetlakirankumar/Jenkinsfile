pipeline {
  agent {
    docker { image 'httpd' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'mv . /var/www/html'
      }
    }
  }
}
