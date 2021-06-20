pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo "Testing polling log"'
            }
        }
        stage('BuildMore') {
            steps {
                bat '''
                    echo "Multiline shell steps works too"
                    bash -c "ls -lah"
                '''
            }
        }
    }
}
