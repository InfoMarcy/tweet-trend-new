pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Clone-git-code') {
            steps {
                git branch: 'main', url: 'https://github.com/InfoMarcy/tweet-trend-new.git'
            }
        }
    }
}
