pipeline {
  agent any
  
  stages {
    stage("build") {
      steps {
        echo 'building...'
        sh pwd
      }
    }
    stage("test") {
      steps {
        echo 'testing...'
      }
    }
    stage("deploy") {
      steps {
        echo 'deploying...'
      }
    }
  }
}
