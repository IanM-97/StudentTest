pipeline {
    agent any
	
    stages 
	{
        stage('Build') 
		{
		steps 
			{
			echo 'Building..'
			bat 'build.bat'
			}
        	}
        stage('Test') 
		{
            	steps 
			{
                	echo 'Testing..'
					bat 'test.bat'
            		}
        	}
    	}
}