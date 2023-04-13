pipeline {
  agent {
    docker { image 'httpd' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'ssh mv source/* /usr/local/apache2/htdocs/'
      }
    }
  }
}
