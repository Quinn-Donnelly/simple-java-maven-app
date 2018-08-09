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
                echo 'Testing (go for 6 from github THIS ONE FOR SURE)'
            }
        }
        stage('Deliver') {
            steps {
                echo 'Delivering'
            }
        }
    }
}
