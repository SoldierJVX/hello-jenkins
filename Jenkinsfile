pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello Jenkins" > /home/joaosilva/Desktop/teste.txt'
            }
        }
    }
}