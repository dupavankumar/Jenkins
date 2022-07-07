pipeline {
	agent any
	stages{
		stage('Stage1'){
			steps{
				echo 'Hai........'
				echo 'Hello......'
			}
		}
		stage('Stage2'){
			steps{
				echo "We are in 'main' branch"
				sh 'chmod 777 README.md'
			}
		}
		stage('README file'){
			steps{
				sh 'cat README.md'
			}
		}
	}
}
