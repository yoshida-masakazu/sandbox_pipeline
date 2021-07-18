pipeline {
    agent {
        label 'master'
    }
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hello2') {
            steps {
                sh """
                    echo 'Hello World2'
                    hostname
                    pwd
                """
            }
        }
        stage('Hello3') {
            steps {
                sh """
                    echo 'Hello World3'
                    ls -al
                """
            }
        }
        stage('Hello4') {
            steps {
                echo 'Hello World4'
                echo 'My first Jenkinsfile'
            }
        }
    }
}
