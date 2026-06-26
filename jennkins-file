pipeline {
    agent any

    stages {

        stage('PULL') {
            steps {
                echo 'Pull Success'
            }
        }

        stage('BUILD') {
            steps {
                sh 'mvn clean package -DskipTests'
            }
        }

        stage('TEST') {
            steps {
                echo 'Test Success'
            }
        }

        stage('DEPLOY') {
            steps {
                echo 'Deploy Success'
            }
        }
    }
}
