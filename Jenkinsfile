pipeline {
  agent any
  stages {
    stage('') {
      steps {
        bat(script: 'echo \'hi\'', returnStatus: true, returnStdout: true)
        build(job: 'my job', quietPeriod: 1)
      }
    }

  }
}