pipeline {
    agent {label 'Linux'}

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
