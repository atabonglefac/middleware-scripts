pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello '
                sleep 5
            }
        }
             stage('build') {
            steps {
                echo 'build'
                sleep 5
            }
        }
             stage('test') {
            steps {
                echo 'test'
                sleep 4
            }
        }
             stage('deploy') {
            steps {
                echo 'deploy'
                sleep 4
            }
        }
    }
}
