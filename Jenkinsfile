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
                echo 'Testing (go for 6 from github2)'
            }
        }
        stage('Deliver') {
            steps {
                echo 'Delivering'
            }
        }
    }
}
