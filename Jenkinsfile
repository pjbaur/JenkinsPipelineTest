pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
          sh '''
        echo "PATH = ${PATH}"
        env
        '''
      }
    }

    stage('Build') {
        steps {
            echo 'Building...'
        }
    }
  }
}
