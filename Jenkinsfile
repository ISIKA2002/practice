pipeline {
  agent any
  stages {

    stage('Compile') {
      steps{
        sh 'mvn clean compile'
      }
    }
     stage('Hello') {
      steps{
        sudo 'hello world'
}
}
    stage('UnitTest') {
      steps{
        sh 'mvn clean test'
      }
    }

    stage('Package') {
      steps{
        sh 'mvn clean package'
      }
    }
}
}
