pipeline {
    agent {label 'agent-ec2'}

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