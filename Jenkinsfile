pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "last bonjour aurevoir"
            }
        }
        stage('test docker') {
            steps {
                @docker run hello-world
            }
        }
    }
}
