pipeline {
    agent any

    stages {
        stage('clone from github') {
            steps {
                git branch: 'main', url: 'https://github.com/nidheeshnle/jenkins_pipeline_testing.git'
            }
        }
        stage('build') {
            steps {
                echo 'build'
            }
        }
        stage('testing') {
            steps {
                echo 'testing'
            }
        }
        stage('deployment') {
            steps {
                echo 'deployment'
            }
        }
    }
}
