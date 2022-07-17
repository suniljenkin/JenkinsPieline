pipeline{
    agent any
    
    stages {
        stage('Build'){
            steps{
                 echo 'Hello World sunil kumar'
            }
        }
        stage('Deploy'){
            steps{
                 echo 'Hello World deploying'
            }
        }
        stage('Test'){
            steps{
                 echo 'Hello World Testing'
            }
        }
        stage('Release'){
            steps{
                 echo 'Hello World Release'
                mail bcc: '', body: 'Test email from jenkins', cc: '', from: '', replyTo: '', subject: 'Test email from jenkins', to: 'nsunilkumarreddy34@gmail.com'
            }
        }
    }
    
}
