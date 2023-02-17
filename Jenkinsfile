pipeline{
	agent any
	stages {
		stage('Clone Git') {
			steps {
				git 'https://github.com/Tejinder7/JenkinsDemo.git'
			}
		}
		stage('Build Code'){
			steps {
				sh "chmod u+x a.sh"
				sh "./a.sh"
			}
		}
	}
}
