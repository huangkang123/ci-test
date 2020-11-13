pipeline{
    agent any
		
    stages {
        stage('Build') {
				   
            steps{
                echo 'This is a build step' 
								sh "printenv"
            }
        }
        stage('check') {
            steps{
                echo 'This is a test step'
                checkout scm								
            }
        }
				stage('Test2') {
            steps{
                echo 'This is a test step'
                echo 'df -h'								
            }
        }
        
			
    }
}
