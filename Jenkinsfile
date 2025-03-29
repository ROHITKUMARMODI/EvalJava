pipeline{
    agent any
    tools{
        nodejs 'Nodejs'
    }
    stages{
          stage('Checkout'){
            steps{
              git-url 'https://github.com/ROHITKUMARMODI/EvalJava.git',branch 'main'
            }
        }
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
