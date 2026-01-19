pipeline {
    agent {
        node {
            label 'maven'
        }
    }

environment {
    PATH = "${env.PATH}:/usr/share/maven/bin"
}
    stages {
        stage('build') {
            steps {
                sh 'mvn clean deploy'
            }
        }
    }
}
