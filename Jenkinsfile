  
pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
          echo 'Build Stage'
          bat 'mvn clean'
          bat 'mvn compile'
          }
      }
      stage('Test'){
          steps{
          echo 'mvn Test'
          bat 'mvn test'
          }
      }
       stage('Deploy'){
          steps{
          echo 'Deploy Stage'
          bat 'mvn deploy'
          }
      }
    }
}