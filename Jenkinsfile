pipeline {
    agent {
        node {
            label 'linux && java11'
        }
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello Pipeline'
            }
        }
        stage('Clone') {
            steps {
                echo 'cloning...'
            }
        }
    }
}
