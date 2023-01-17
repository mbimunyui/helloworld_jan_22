pipeline {
    agent any
    stages{
      stage('Hello'){
       steps {
         echo "Hello World Github"
       }
      }
       stage('Build'){
        steps{
          echo "Build step"
          sleep(10)
        }
       }
       stage('Test'){
        steps{
          echo "Test Step"
        }
       }
       stage('Deploy'){
        steps{
          echo "Deploy Step"
          sleep 10
        }
       }
       stage('Docker'){
       steps {
        echo "Docker image"
       }
       }
    
    
    }
  
}
