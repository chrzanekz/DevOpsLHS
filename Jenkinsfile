pipeline {
    agent any
    stages {
        stage('git') {
            steps {
                git branch: 'main', url: 'https://github.com/chrzanekz/DevOpsLHS.git'
            }
        }
        stage('cron1') {
            steps {
              sh 'cat README.md'
            }
        }
    }
}
