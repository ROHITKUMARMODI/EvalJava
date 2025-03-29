pipeline{
    agent any
    tools{
        NodeJs 'Nodejs'
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
