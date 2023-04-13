pipeline {
  agent {
    docker { image 'httpd' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'mv source/* /usr/local/apache2/htdocs/'
      }
    }
  }
}
