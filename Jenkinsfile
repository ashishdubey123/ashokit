pipeline {
    agent any
    tools {
        maven 'MAVEN'
    }
    stages {
        stage('git pull') {
            steps{
                git branch: 'main', url: 'https://github.com/ashishdubey123/ashokit.git'
            }
        }
        stage('mvn clean'){
            steps{
                sh 'mvn clean'
            }
        }
        
    }
}
