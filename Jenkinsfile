pipeline{
    agent any
		
    stages {
        stage('Build') {
				   
            steps{
                echo 'This is a build step' 
								sh "printenv"
            }
        }
        stage('Test') {
            steps{
                echo 'This is a test step'
                echo 'test222'								
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
