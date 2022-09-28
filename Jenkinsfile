properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'running .py:  '
                bat 'python HiThere.py'
            }
        }
    }
}
