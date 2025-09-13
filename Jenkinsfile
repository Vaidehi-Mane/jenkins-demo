pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello from Jenkins pipeline!'
            }
        }
        stage('Holla') {
            steps {
                echo 'Congrats on 1st trigger'
            }
        }
        stage('create') {
            steps {
               bat 'mkdir "C:/ProgramData/Jenkins/.jenkins/workspace/Demo CICD/Trigger"'
            }
        }
    }
}
