pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'Job is started...'
//                 sh 'chmod +755 ./job2.sh'
                sh 'echo "Path is: $(pwd)"'
                sh 'bash ./job2.sh'
            }
        }
    }
}