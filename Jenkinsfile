// pipeline {
//     agent {
//         docker { image 'node:14-alpine' }
//     }
//     stages {
//         stage('Test') {
//             steps {
//                 sh 'node --version'
//             }
//         }
//     }
// }
node {
	docker.image('python:latest').inside {
		sh 'python --version' 
	}
}