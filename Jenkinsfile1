pipeline {
    agent any// Para definir DONDE QUIERO QUE SE EJECUTE ESTA TAREA
    stages {
        stage("Etapa 1") {
            steps {  // Hacemos las llamadas a los plugins
                sh "echo Soy la etapa 1" // Laamada al plugin que ejecuta un shell
            }
        }
        stage("Etapa 2") {
            steps {
                sh "echo Soy la etapa 2"
                sh """
                echo Soy la etapa 3
                echo Acabo la etapa 3
                """
            }
            
        }
    }
}