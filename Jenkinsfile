pipeline {

    agent {
        node {
            label 'master'
        }
    }

    stages {
        stage(' Test') {
            steps {
                sh """
                echo "Running Unit Tests"
                """
            }
        }
    }   
}
