node('master')
{

	stage('Git Cloning')
	{
		println "Cloning Repo"
		git 'https://github.com/TJ726/DemoJob.git'

		
		
	}
	stage('Run Test Case')
	{
		steps {
			sh”””
			export LOC = $home/sample
			rm $LOC
			mkdir $LOC
			cd $LOC
			echo "reached"		
			“””
		}
	}
	
}