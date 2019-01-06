pipeline {
    agent any
	
    stages 
	{
        stage('Build') 
		{
			tools 
			{
				JDK "jdk1.8.0_121"
			}
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