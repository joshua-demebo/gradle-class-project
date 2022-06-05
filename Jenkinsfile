pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'echo \'Running QA phase...\'', propagate: true, quietPeriod: 1)
      }
    }

  }
}