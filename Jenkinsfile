pipeline {
  agent any
  triggers {
        githubPush()
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
