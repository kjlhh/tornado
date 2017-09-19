pipeline {
  agent any
  stages {
    stage('') {
      steps {
        parallel(
          "test2": {
            echo 'test2 done'
            
          },
          "test3": {
            echo 'test3 done'
            
          },
          "test1": {
            echo 'test1 done'
            
          }
        )
      }
    }
    stage('check host') {
      steps {
        echo 'check host done'
      }
    }
    stage('some check') {
      steps {
        echo 'some check'
      }
    }
    stage('done') {
      steps {
        echo 'done'
      }
    }
  }
}