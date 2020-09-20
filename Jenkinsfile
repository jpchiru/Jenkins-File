pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
		echo "Time now is: " `time`
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
