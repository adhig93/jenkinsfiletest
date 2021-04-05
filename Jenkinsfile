pipeline {
    agent any

    stages {
        stage('Stage1:Build') {
            steps {
                sh '''
                    #!/bin/bash
                    cd /home/ec2-user/jenkins/cpipeline/test_repo
                    git pull
                    make
                   '''              
            }
        }
        stage('Stage2:Test') {
            steps {
                echo 'This is Test Stage'
            }
        }
        stage('Stage3:Deploy') {
            steps {
                echo 'This is Deploy Stage'
            }
        }
    }
}    
