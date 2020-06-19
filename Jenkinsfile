pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'IS Building..'
                echo 'Building Environment: $VAR'
                dir('projectAAAAAA'){
                    git url: 'https://github.com/jaxhsu/jenkins-pipeline.git', branch: 'sample'
                }
            }
        }
        stage('Test') {
            steps {
                echo 'IS Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'IS Deploying....'
            }
        }
    }
}