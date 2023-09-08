pipeline{
    agent any
    stages{
        stage("checkout code") {
            steps{
                sh "git clone https://github.com/utkarshkushwaha/javaP.git"
            }
        }
        stage("check docker version") {
            steps{
                sh "sudo docker version"
            }
        }
    }
}
