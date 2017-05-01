pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World 2 - diff branch'
            }
        }
    }
    post {
        always {
            echo 'I will always say Hello again!'
        }
    }
}