pipeline {
    agent any

    stages {
        stage('Dockerize simple nodejs app') {
            steps {
                sh "echo $BRANCH_NAME" 
            }
        }
    }
    post {
        success {
            echo "wallah w 3mloha el regala"
        }
    }
}