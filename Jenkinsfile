pipeline {
  agent any
  triggers {
        pollSCM()
      }
  
  
  stages {
    stage("hello") {
      steps {
        echo 'hello'
     }
      }
      stage("world") {
      steps {
        echo 'world'
      }
    }
  }
    
}
