pipeline {
    agent any

    stages {
        stage("Checkout stage") {
            steps {
                echo "Checkout stage"
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