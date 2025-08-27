pipeline {
    agent any

    stages {
        stage('Hello Jenkins') {
            steps {
                echo 'Hello, World from Jenkins!'
            }
        }
        
        stage('Hello Docker') {
            steps {
                sh 'docker run --rm hello-world'
            }
        }
    }
}
