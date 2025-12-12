pipeline {
    agent any
    stages {
        stage('Run fibonacci git') {
            steps {
               powershell('powershell -ExecutionPolicy Bypass -File ./scripts/fibonacci.ps1')
            }
        }
    }
}
