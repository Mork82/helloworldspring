pipeline {
  agent any

   tools {
    maven 'mavenjenkins' 
  }

  stages {
    stage('Build') {
      steps {
        // Build the Maven project
        sh 'mvn clean build'
      }
    }
    
  }
}
