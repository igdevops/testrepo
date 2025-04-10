pipeline {
    agent {label 'cicd6'}

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
		sh 'git --version'
                sh 'git config --global --get http.proxy'
            }
        }
    }
}
