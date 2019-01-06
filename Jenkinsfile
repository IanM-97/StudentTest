pipeline {
    agent any

    stages {
        stage('Build') {
		tools {
               JDK "jdk-1.8.0_181"
            }
            steps {
                echo 'Building..'
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