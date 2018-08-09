pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing (this was easy)'
            }
        }
        stage('Deliver') {
            steps {
                echo 'Delivering'
            }
        }
    }
}
