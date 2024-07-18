pipeline{
    agent {
        label "worker"
    }
    stages{
        stage("make directory"){
            steps{
                sh "mkdir ~/jenkins-demo || true"
            }
        }
        stage("add files"){
            steps{
                sh "touch ~/jenkins-demo/file1.txt"
            }
        }
    }
}
