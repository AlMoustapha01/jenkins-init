pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building application..'
                scripts{
                    def test = 22+5>60? 'faux':'vrai'
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
