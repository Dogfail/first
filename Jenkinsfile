pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo 'building the app'
            }
        }
        stage('Test') {
	when {
		expression{
				BRANCH_NAME = 'feature_x'
				}

} 
            steps {
                echo 'testing the app'
            }
        }
        stage('Deploy') { 
            steps {
                echo 'deploing the app'
            }
        }
    }
}
