pipeline {
    agent any
	
    stages 
	{
        stage('Build') 
		{
			steps 
			{
				echo 'Building..'
				javac studentTest.java
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