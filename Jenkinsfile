@Library('my-shared-lib') _

pipeline {
    agent any

    stages {
        stage('Test Shared Lib') {
            steps {
                script {
                    buildApp()
                    deployApp("dev")
                    sayHello("Srikanth")
                }
            }
        }
    }
}
