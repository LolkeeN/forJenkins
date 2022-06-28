pipeline {
    agent any

    stages {
        stage('1-Build') {
            steps {
                echo 'Start of stage build'
                echo 'Building...'
                echo 'End of Stage Build'
            }
        }
        stage('2-Test') {
            steps {
                echo 'Start of stage test'
                echo 'Building...'
                echo 'End of Stage test'
            }
        }
        stage('3-Deploy') {
            steps {
                echo 'Start of stage deploy'
                echo 'Building...'
                echo 'End of Stage deploy'
            }
        }
    }
}
