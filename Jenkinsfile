pipeline {
    agent any

    stages 
	{
        stage('Build') 
		{ 
			steps 
			{
				echo 'Building..'
				javac -version
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