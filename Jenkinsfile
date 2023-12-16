pipeline {
    agent any

    stages {
        stage('Checkout from GitHub') {
            steps {
                script {
                    // GitHub repository URL
                    def gitRepoUrl = 'https://github.com/EnesAkil/case-projects.git'

                }
            }
        }

        stage('Build') {
            steps {
                script {
                    
                    sh 'node app.js' //
                }
            }
        }
        

        stage('Test') {
            steps {
                script {
                    
                    sh 'whoami' 
                }
            }
        }

        stage('Deploy') {
            steps {
                script {
                    // Add your deployment steps here
                    sh 'app.js' // Örnek: Bir deploy script'i çalıştırma
                }
            }
        }

        stage('Deploy') {
            steps {
                script {
                    
                    sh 'docker image build -t .' // 
                }
            }
        }
    }
}
