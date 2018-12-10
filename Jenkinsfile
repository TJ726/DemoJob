node('master')
{

	stage('Git Cloning')
	{
		println "Cloning Repo"
		git 'https://github.com/TJ726/DemoJob.git'

		
		
	}
	stage('Run Test Case')
	{
		sh 'echo "test"'
		/*
		sh'''
		EXPORT LOC = $home/sample
		rm $LOC
		mkdir $LOC
		cd $LOC
		echo "reached"		
		'''
		*/
	}
	
}