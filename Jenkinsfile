pipeline {
    agent any
    parameters {
        string(name: 'N', defaultValue: '10', description: 'How many Fibonacci numbers?')
    }
    stages {
        stage('Run fibonacci git') {
            steps {
               powershell('powershell -ExecutionPolicy Bypass -File ./scripts/fibonacci.ps1 -N ${env:N}')
            }
        }
    }
}
