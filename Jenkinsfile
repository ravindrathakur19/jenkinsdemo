pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello from Jenkins!'
            }
        }

        stage('Run Python') {
            steps {
                git 'https://github.com/USERNAME/jenkins-demo.git'
                bat 'python hello.py'
            }
        }
    }
}
