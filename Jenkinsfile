pipeline {
    agent any
    stages {
        stage('clone') {
            steps {
                git 'https://github.com/sumanyuvaraj/Studentapp.git'
            }
        }
        stage('clean'){
        steps{
            sh 'mvn clean'
        }
    }
}
}
