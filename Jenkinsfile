pipeline {
    agent any
    stages{
        stage('buld code'){
            steps {
                echo "build code"
            }
        }
        stage('deploy code'){
            when {
                branch 'master'
            }
            steps {
                echo "deploy code"
            }
        }
    }
}