pipeline {
    agent any
	
	env.JAVA_HOME="${tool 'jdk1.8.0_121'}"
	env.PATH="${env.JAVA_HOME}/bin:${env.PATH}"

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