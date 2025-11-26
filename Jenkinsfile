pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                script{
                    // Sample Groovy code
                    def greet(name) {
                        return "Hello, ${name}!"
                    }
                    echo greet('Jenkins')
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}