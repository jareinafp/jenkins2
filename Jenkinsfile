 pipeline {
        agent any
        stages {
            stage('Checkout') {
                steps {
                    git 'https://github.com/jareinafp/jenkins2'
                }
            }
            stage('Ejecutar Hola Mundo') {
                steps {
                    sh 'python hola_mundo.py' // Reemplaza con el nombre de tu archivo
                }
            }
        }
    }
