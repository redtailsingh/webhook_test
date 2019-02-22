//1
pipeline {
    agent any
    stages {
        stage('say hello') {
            steps {
                echo 'hello there!'
		//githubNotify description: 'This is a shorted example', status: 'SUCCESS', credentialsId: '156de836-c2fd-4434-9f84-eb3e5e4ffdce', sha: "${GIT_COMMIT}", repo: "${GIT_BRANCH}"
                echo "${GIT_COMMIT} ${GIT_BRANCH}"
	    }
        }
        stage('say bye') {
            steps {
                echo 'bye there!! '
            }
        }
    }
}
