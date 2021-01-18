pipeline {
  agent any
  stages {
  stage('dev') {
      steps {
        script {
          echo 'Stage 1-This dev step'
        }
      }
    }
  stage('Stage qa') {
      steps {
        script {
          echo 'Stage 2 - This is qa'
        }
      }
    }
  stage('Stage prod') {
      steps {
        script {
          echo 'Stage 3 - This is prod'
        }
      }
    }
  }
}
