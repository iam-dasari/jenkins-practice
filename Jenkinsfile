pipeline {
    agent any

    options {
        (time: 60, unit: 'SECONDS')
    }

    stages {
        stage("Checkout stage") {
            steps {
                sh "Checkout stage"
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