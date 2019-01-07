pipeline {
    agent any
	
    stages 
	{
	stage('Fetch') 
		{
		steps 
			{
			git url:git://github.com/IanM-97/StudentTest.git, branch:'master'
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
            }
        }
    }
}