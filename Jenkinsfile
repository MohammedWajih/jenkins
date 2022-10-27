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
            git(url: 'https://github.com/MohammedWajih/store.git', branch: 'main')
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