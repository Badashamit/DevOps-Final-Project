pipeline {
    agent any
    environment {
        GITHUB_TOKEN = credentials('GitHub-Credentials')
    }
    stages {
        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/Badashamit/DevOps-Final-Project.git',
                    credentialsId: 'GitHub-Credentials'
            }
        }
    }
}

