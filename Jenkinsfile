pipeline{
    agent any
    stages{
        stage('Clone gitlab1'){
            steps{
                git branch: 'develop', url: 'https://github.com/nambh911/github1.git'
            }
        }
    }
    post{
        always{
            mail bcc: '', body: 'Nam123456', cc: '', from: '', replyTo: '', subject: 'Hi Nam', to: 'nambh911@gmail.com'
        }
    }
}

