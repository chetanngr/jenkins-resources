pipeline {
    agent any
    
        tools {
        jdk 'openjdk-11'
        maven 'maven 3.6.3'
        dockerTool 'docker-latest'
    }
       environment {
        NAME = 'ricardo'
        LASTNAME = 'gonzalez'
    }

    stages {
        stage('Build') {
            steps {
                sh 'echo $NAME $LASTNAME'
            }
        }
    }
}
