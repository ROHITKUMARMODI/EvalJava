pipeline{
    agent any
    tools{
        maven 'Maven'
    }
    stages{
        stage('Build'){
            steps{
              bat 'npm run build'
            }
        }
         stage('Test'){
            steps{
              bat 'npm test'
            }
        }
    }
}
