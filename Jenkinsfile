pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    touch /myfolder/mypipeline.txt			
                    ls -lah
                '''
            }
        }
    }
}


