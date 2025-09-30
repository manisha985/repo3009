node('built-in') 
{
    stage('Continuous Download master') 
	{
    git 'https://github.com/yankils/hello-world.git'
	}
    stage('Continuous Build master') 
	{
    sh label: '', script: 'mvn package'
	}
	}
 
