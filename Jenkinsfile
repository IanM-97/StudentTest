pipeline {
    agent any

    stages {
        stage('Build') {
		set PATH="C:\Program Files\Java\jdk1.8.0_31\bin"
		javac -version 
		tools {
               JDK "jdk1.8.0_121"
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