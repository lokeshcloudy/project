pipeline {
    agent any
    tools {
        gradle 'Gradle'
        maven 'maven'
    }
    stages {
        stage("DockerLogin") {
            steps {
                script {
                    sh 'printenv'
                }
            }
        }
