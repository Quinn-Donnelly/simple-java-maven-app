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
                echo '(>^_^)>'
            }
        }
        stage('Deliver') {
            steps {
                echo '<(^_^<)'
            }
        }
    }
}
