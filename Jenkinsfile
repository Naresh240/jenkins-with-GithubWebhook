pipeline {
    agent any
    stages {
        stage ('SCM') {
            steps {
                git branch: 'main', url: 'https://github.com/Naresh240/jenkins-with-GithubWebhook.git'
            }
        }
        stage ('Build Artifact') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
