pipeline {
  agent any
  
  tools {
    dotnetsdk '6.0'
  }
  
  stages {
    stage("build") {
      steps {
        echo 'building...'
        pwd
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
