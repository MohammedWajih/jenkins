pipeline {
  agent any
  stages {
    stage('Building Stage') {
      parallel {
        stage('Building Stage') {
          steps {
            echo 'Welcoome to Build Stage'
          }
        }

        stage('Checkout Stage') {
          steps {
            echo 'Welcome to Checkout Stage'
            git(url: 'https://github.com/MohammedWajih/store.git', branch: 'main', credentialsId: '868d2f4f-20da-4172-b833-99ba04b48525')
          }
        }

      }
    }

    stage('Testing tage') {
      steps {
        echo 'Welcome to Testing Stage'
      }
    }

    stage('Deployment Stage') {
      steps {
        echo 'Welcoome to Deployment stage'
      }
    }

  }
}