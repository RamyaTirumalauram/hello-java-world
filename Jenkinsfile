pipeline {
    agent any
    stages{
        
    stage ('Checkout')
    {
        steps{
          sh "checkout scm"
        }
    }
    stage ('clean install')
    {
    steps{
        sh "mvn clean install"
    }
    }
}  
}
