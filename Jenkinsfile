pipeline {
  agent any
  stages {
    stage('Docker build') {
      steps {
        sh 'sudo docker build -f Dockerfile.Spark3.2.1Nessie0.28.0Delta.yml .'
      }
    }

  }
}