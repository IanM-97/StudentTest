pipeline {
    agent any
	
    stages 
	{
	stage('Fetch') 
		{
		steps 
			{
			git url: 'https://github.com/IanM-97/StudentTest.git'
			}
        }
        stage('Build') 
		{
		steps 
			{
			bat 'build.bat'
			}
        }
        stage('Test') 
		{
            steps 
			{
			bat 'test.bat'
			ohsdjks
            }
        }
    }
}