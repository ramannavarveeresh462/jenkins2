pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'building'
            }
        }
        stage('Test') { 
            steps {
                echo 'testing'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'deploying'
                
            }
        }
       stage('Notify') { 
            steps {
                echo 'Notifying'
                sh "./mail.sh"
                
            }
        } 
    }
}
