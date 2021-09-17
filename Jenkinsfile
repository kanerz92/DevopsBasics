pipeline {
  
  agent any
  
  stages {
    
    stage("build") {
      
      steps { 
        sh 'mvn -B -DskipTests clean package'
        echo ' building app'
      }     
    }
    stage("test") {
      
      steps { 
        sh 'mvn test'
        echo ' testing app'
      }     
    }
    stage("deploy") {
      
      steps { 
        echo 'need to deploy here'
      }     
    }
  }
  
}
