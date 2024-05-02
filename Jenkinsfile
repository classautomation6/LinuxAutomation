pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps work too"
                    touch /myfolder/pipeline.txt 
                    ls -lah
                '''
            }
        }
    }
}
