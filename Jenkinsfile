pipeline {
    //agent any
	agent {
        	docker { image '16.04' }
    	}

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		sh 'echo $env'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
