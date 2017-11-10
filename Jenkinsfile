pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo "Building the task code..."
mvn -version
mkdir -p target
touch "target/spring-boot.war"'''
      }
    }
  }
}