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
       stage('Deploy elinks to the server') {
            steps {
                sh 'sudo yum install elinks -y'
            }
        }
       stage('Deploy to Kubernetes Cluster') {
            steps {
                sh 'sudo yum install telnet -y 
            }
        }

    }
}


