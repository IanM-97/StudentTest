pipeline {
    agent any
	
    stages 
	{
        stage('Build') 
		{
			steps 
			{
				echo 'Building..'
				javac student.java
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