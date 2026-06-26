pipeline {
    agent any

    stages {

        stage('Deploy to Test') {
            steps {
                build job: 'testjob'
            }
        }

        stage('Deploy to Production') {
            steps {
                build job: 'prodjobs'
            }
        }
    }
}
