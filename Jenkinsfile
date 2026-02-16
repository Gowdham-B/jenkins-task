pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
    }

    post {
        success {
            echo 'Build was Successful!'
        }
        failure {
            echo 'Build Failed!'
        }
    }
}
