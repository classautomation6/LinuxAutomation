pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    touch /home/ajudithpipeline.txt
                    ls -lah
                '''
            }
        }
    }
}

