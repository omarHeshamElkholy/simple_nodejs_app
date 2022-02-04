
pipeline {
    agent { label 'ec2-agent' }

    stages {
        
        
        stage('Stage 1') {
            steps {
                sh ''' 
                    docker build -t testapp:v1 .
                    docker run testapp:v1
                '''
            }
        }
        
    }
}
