pipeline {
    agent any
    stages {
        stage("Setup") {
            steps {
                echo "setup"
            }
        }
        stage("Confirm") {
            steps {
                echo "confirm"
            }
        }
        stage("Build") {
            steps {
                echo "mvn clean install"
            }
        }
        stage("Deploy") {
            steps {
                echo "deploy"
            }
        }
        stage("Tests") {
            steps {
                echo "tests"
            }
        }
    }
}