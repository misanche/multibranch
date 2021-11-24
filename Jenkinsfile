pipeline {

    agent {
        node {
            label 'master'
        }
    }

    stages {
        stage(' Test') {
            steps {
                build job: "/multibranch2/" + env.BRANCH_NAME.replaceAll("/", "%2F"), parameters: [[$class: 'StringParameterValue', name: 'VERSION_NUMBER', value: '1.0.0.0']]
            }
        }
    }   
}
