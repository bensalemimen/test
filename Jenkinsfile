pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/bensalemimen/test.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Compilation du projet...'
                sh 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                echo 'Exécution des tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Déploiement terminé ✅'
            }
        }
    }
}
