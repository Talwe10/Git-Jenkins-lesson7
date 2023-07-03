pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                    ls -l
                    python3 Hi-from-J.py
            }
        }
    }
}
