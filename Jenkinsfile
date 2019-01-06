pipeline {
    agent any
	
    stages 
	{
        stage('Build') 
		{
			tools 
			{
				JDK "JAVA_HOME"
			}
			steps 
			{
				echo 'Building..'
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