pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    touch /myfolder/pipeline.txt			
                    ls -lah
                '''
            }
        }
       stage('Deploy to Kubernetes Cluster') {
            steps {
                sh 'yum install elinks -y'
            }
        }

    }
}


