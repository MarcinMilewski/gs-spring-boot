pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World 2, master pooling test 6'
            }
        }
    }
    post {
        always {
            echo 'I will always say Hello again!'
        }
    }
}