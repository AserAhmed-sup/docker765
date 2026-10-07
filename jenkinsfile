pipeline {
    agent {
        label 'docker'
    }
    stages {
        stage('Build docker image') {
            steps {
                script {
                    sh 'docker build -t AserAhmed/docker-react -f dockerfile.dev .'
                }
            }   
        }
    stages ('run Tests') {
        steps {
            script {
                sh 'docker run -e CI=true AserAhmed/docker-react npm run test'
            }
        }
    }
}
}