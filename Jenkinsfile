pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('UNIT') {
            steps {
                echo 'Execution des tests unitaire'
            }
        }
        
        stage('BUILD') {
            steps {
                echo 'Generation du build'
            }
        }
        
        stage('E22') {
            steps {
                echo 'Test e2e'
            }
        }
        
        stage('DPLOY') {
            steps {
                echo 'Deploiement'
            }
        }
    }
}
