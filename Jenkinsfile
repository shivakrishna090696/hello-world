pipeline {
    agent any
    stages {
        stage ('checkout source') {
            steps {
                git branch: 'master', url: 'https://github.com/shivakrishna090696/hello-world.git'
            }
        }
        stage ('java build') {
            steps {
                sh 'mvn --version'
             }
        }
    }
}
