pipeline {
  agent {
    docker { image 'httpd' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'cp source/* /usr/local/apache2/htdocs/'
      }
    }
  }
}
