pipeline {
    agent {
        docker {
            image 'maven:3.8.7-openjdk-17'
        }
    }
    stages {
        stage('Compilar Java (Maven)') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}

