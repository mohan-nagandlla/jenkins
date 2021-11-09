pipeline {
    agent {
        docker { image 'nsc-registry.infra.ericsson.se:5000/node:14' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
