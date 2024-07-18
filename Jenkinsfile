pipeline{
    agent any
    stages{
        stage("make directory"){
            steps{
                sh "mkdir ~/jenkins-demo"
            }
        }
        stage("add files"){
            steps{
                sh "touch ~/jenkins-demo/file1.txt"
            }
        }
    }
}