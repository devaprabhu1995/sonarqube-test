pipeline{
    agent 'node1'
    stages{
    
      stage('Test'){
          steps{
          sh 'mvn test'
          }
      }
      stage('Build'){
          steps{
          sh 'mvn install'
          }
      }
      stage('Deploy'){
          steps{
          sh 'mvn deploy'
          }
      }
      
    }
}
