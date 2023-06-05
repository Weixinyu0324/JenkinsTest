pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        timestamps()
        sh '''
echo "building........."'''
      }
    }

    stage('test') {
      steps {
        timestamps()
        sh 'echo "testing...."'
      }
    }

    stage('deploy') {
      steps {
        sh 'echo "deploying...."'
        timestamps()
      }
    }

  }
}