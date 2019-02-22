//1
pipeline {
    agent any
    stages {
        stage('say hello') {
            steps {
                echo 'hello there!'
		githubNotify description: 'This is a shorted example',  status: 'SUCCESS'
            }
        }
        stage('say bye') {
            steps {
                echo 'bye there!! '
            }
        }
    }
}
