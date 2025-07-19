pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Clona el repositorio desde GitHub
                git 'https://github.com/Kreighner/laboratorioJenkins.git'
            }
        }

        stage('Compilar Java (Maven)') {
            steps {
                // Ejecuta Maven directamente
                sh 'mvn clean install'
            }
        }
    }
}
