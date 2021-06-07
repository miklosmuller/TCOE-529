pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		sh "javac tcoe-529.java"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
		sh "java HelloWorld"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
		echo 'this is not in scope right now'
            }
        }
    }
}
