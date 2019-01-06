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