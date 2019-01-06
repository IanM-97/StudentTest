pipeline {
    agent any
	
    stages 
	{
        stage('Build') 
		{
			steps 
			{
				echo 'Building..'
				javac Student.java
			}
        }
        stage('Test') 
		{
            steps 
			{
                echo 'Testing..'
            }
        }
    }
}