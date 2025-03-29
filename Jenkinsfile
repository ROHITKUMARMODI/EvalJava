pipeline{
    agent any
    tools{
        nodejs 'Nodejs'
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
        stage('Deploy'){
            steps{
              bat 'deploy a Node.js application'
            }
        }
    }
}
