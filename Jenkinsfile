pipeline {
  agent none
  stages {
    stage('Build') {
                    agent any
                    options {
                            skipDefaultCheckout()
                    }
      steps {
        echo 'Hello World for multiline'
        echo 'Check the output in master also'
      }
    }
  }
}
