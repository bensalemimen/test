pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Récupération du code...'
            }
        }

        stage('Run Python Script') {
            steps {
                echo 'Exécution du script Python 🚀'
                bat 'python main.py'
            }
        }

        stage('Success') {
            steps {
                echo '✅ Pipeline terminé avec succès !'
            }
        }
    }
}
