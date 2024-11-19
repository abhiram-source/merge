pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage("build") {
            steps {
                echo "application is building"
            }
        }
       stage("test") {
            steps {
                echo "application is testing"
            }
        }
       stage("deploy") {
            steps {
                echo "application is deploying"
            }
        }
    }
}
