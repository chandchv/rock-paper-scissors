pipeline {
    agent { docker { image 'maven:latest' } }
      stages {
        stage('log version info') {
      steps {
        sh 'mvn --version'
        sh 'mvn clean install'
      }
    }
  }
}
