pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      parallel {
        stage('Buzz Buzz') {
          steps {
            echo 'Bees Buzz!'
          }
        }

        stage('parallel stage') {
          steps {
            echo 'parallel stage'
          }
        }

      }
    }

    stage('Bees Bees') {
      steps {
        echo 'Buzz, Bees, Buzz!'
        sh 'echo "i\'m ${var1}"'
      }
    }

  }
  environment {
    var1 = 'linda'
  }
}