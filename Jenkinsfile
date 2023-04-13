pipeline {
  agent {
    docker { image 'httpd' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'ssh -o StrictHostKeyChecking=no mv source/* /usr/local/apache2/htdocs/'
      }
    }
  }
}
