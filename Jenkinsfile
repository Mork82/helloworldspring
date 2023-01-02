pipeline {
  agent any

   tools {
    maven 'mavenjenkins' 
  }

  stages {
    stage('Build') {
      steps {
        // Build the Maven project
        sh 'mvn -B -DskipTests clean package'
      }
    }
    
  }
}
