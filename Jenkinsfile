pipeline {
    agent any
	
    stages 
	{
        stage('Build') 
		{
			tools 
			{
				jdk "jdk1.8.0_121";
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