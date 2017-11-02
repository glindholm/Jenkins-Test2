pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
				sh 'echo Test2'
                sh 'mvn --version'
				sh 'echo $PATH'
            }
        }
    }
}