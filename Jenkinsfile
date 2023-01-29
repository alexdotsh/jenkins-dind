pipeline {
    agent  {
        kubernetes {
            label 'dind-agent'
        }
    }

    stages {
        stage("build image") {
            steps {
                script {
                    sh "ls -l"
                    sh "docker ps"
                    sh "docker build -t docker-in-jenkins ."
                }
            }
        }
    }
}
