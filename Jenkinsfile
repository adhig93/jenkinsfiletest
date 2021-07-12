pipeline {
    agent any

    stages {
        stage('Stage1:Build') {
            steps {
                echo "THis is Build Stage"
                sh 'sleep 5'             
            }
        }
        stage('Stage2:Test') {
            steps {
                echo 'This is Test Stage'
                sh 'sleep 5'
            }
        }
        stage('Stage3:Deploy') {
            steps {
                echo 'This is Deploy Stage'
                sh 'sleep 5'
            }
        }
    }
}    
