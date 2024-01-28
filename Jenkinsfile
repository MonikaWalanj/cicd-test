pipeline {
    agent any
    stages {
        stage ('Build Maven') {
            steps {
                sh 'pwd'
                sh 'mv clean install package'
            }
        }
    }
}