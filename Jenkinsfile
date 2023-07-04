properties([pipelineTriggers([cron('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Stage1') {
            steps {
                sh '''
                    ls -l
                    python3 Hi-from-J.py
                '''
            }
        }
    }
}
