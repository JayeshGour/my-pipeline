pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                echo 'I am in Development'
                sh 'git --version'
            }
        }
      stage('Test') {
            steps {
                echo 'I am in Testing'
                sh 'docker --version'
            }
        }
      stage('Prod') {
            steps {
                echo 'I am in Prod'
            }
        }
    }
}
