pipeline {
  agent any
  stages {
    stage('Imprimir MSG') {
      steps {
        echo 'Print blueOcean'
      }
    }

    stage('Fluffy Build') {
      steps {
        sh 'echo Edited Placeholder.'
      }
    }

    stage('Fluffy Test') {
      steps {
        sh 'echo Another Placeholder'
        sh 'sleep 5'
        sh 'echo "Success"'
      }
    }

    stage('Fluffy Deploy') {
      steps {
        echo 'Placeholder'
        emailext(subject: 'Hola', body: 'Este es el body del correo', from: 'jenkins@jenkins.es', to: 'kseto78@gmail.com')
      }
    }

  }
}