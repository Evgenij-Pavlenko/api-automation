pipeline {
  agent any
  stages {
    stage('first') {
      agent any
      steps {
        build(job: 'f1', propagate: true, quietPeriod: 4, wait: true)
      }
    }

  }
}