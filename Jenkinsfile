pipeline {

    agent {
        node {
            label 'master'
        }
    }
    
    environment {
        MIKEL = "MIKEL"                
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
