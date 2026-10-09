// pipeline {
//     agent {
//         label 'docker'
//     }
 
//     stages {
//         stage('Build Docker Image') {
//             steps {
//                 script {
//                     sh 'docker build -t aserahmed/docker-react -f dockerfile.dev .'
//                 }
//             }
//         }
 
//         stage('Tests') {
//             steps {
//                 script {
//                     env.DOCKER_BUILDKIT = 1
//                     sh 'docker run -e CI=true aserahmed/docker-react npm run test'
//                 }
//             }
//         }
//     }
// }
