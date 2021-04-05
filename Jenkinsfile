pipeline {
    agent any

    stages {
        stage('Stage1:Build') {
            steps {
                sh '''
                    #!/bin/bash
                    cd /var/lib/jenkins/workspace/pipeline_test/test_repo
                    git config pull.rebase false
                    git pull https://github.com/adhig93/test_repo
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
