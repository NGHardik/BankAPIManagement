pipeline {
    agent any
 
    stages {
        stage('Hello') {
            steps {
                git branch: 'main', credentialsId: '277bbda2-15d1-4ca8-baa3-712862b9ce13', url: 'https://github.com/NGHardik/BankAPIManagement'
            }
        }
    }
}