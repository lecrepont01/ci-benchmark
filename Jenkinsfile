pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello, World!'
            }
        }
        stage('Goodbye') {
            steps {
                echo 'Goodbye, World!'
            }
        }
        stage('Test') {
            withChecks(name: 'some_other_check') {
                steps {
                    echo 'test!'
                }
            }
        }

    }
}
