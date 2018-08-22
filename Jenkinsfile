pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        mail(subject: 'building with jenkins', body: 'i´m building', from: 'morgado.rodolfo@gmail.com', to: 'morgado.rodolfo@gmail.com')
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}