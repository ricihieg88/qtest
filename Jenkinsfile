pipeline{

agent{

label "windows"
}

tools{
maven 'Maven 3.5.2'
jdk 'java8'
}

stages{
	stage('Initialize')
	{
		steps
		{
			echo "PATH=%PATH%"
			echo "M2_HOME= %M2_HOME%"
		
		}
	}
	stage('Build')
	{
	echo 'Hello World'
	}
}
}
