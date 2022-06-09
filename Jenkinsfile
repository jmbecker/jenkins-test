pipeline {
  agent any
  stages {
    stage('buzz buzz') {
      steps {
        echo 'Bees Buzz!'
      }
    }

    stage('bees bees') {
      steps {
        echo 'Buzz, bees buzz!'
        echo 'Bees Buzzing!'
        echo 'Bees Buzzing Again'
      }
    }
    stage('exec script'){
      steps {
        sh './scripts/helloworld.sh'
      }
    }
    stage('new stage'){
      steps {
        echo 'Another One!'
      }
    }

  }
}