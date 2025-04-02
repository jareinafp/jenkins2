 pipeline {
        agent any
        stages {
            stage('Checkout') {
                steps {
                    git 'URL_DE_TU_REPOSITORIO_GITHUB'
                }
            }
            stage('Ejecutar Hola Mundo') {
                steps {
                    sh 'python hola_mundo.py' // Reemplaza con el nombre de tu archivo
                }
            }
        }
    }
