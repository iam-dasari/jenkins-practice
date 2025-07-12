pipeline {
    agent { node { label 'AGENT-1' } }

    stages {
        stage("Checkout stage") {
            steps {
                echo "Checkout stage with github webhook"
                sh 'ls -lrt'
                sh 'pwd'
            }
        }

    }

    post {
        always {
            echo "Always"
        }
        success {
            echo "Success"
        }
        failure {
            echo "Failure"
        }
    }
}