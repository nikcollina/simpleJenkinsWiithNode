pipeline {
	agent any
	stages{
		stage("Check Node Version"){
			steps {
				sh "node --version"
			}
		}	
		stage("Install Dependencies"){
			steps {
				sh "node --version"
				sh "nom install"
			}
		}
		stage("Test"){
			steps {
				sh "node app.js"
			}
		}
		stage("Release the Version"){
			steps {
				echo "Release the Version"
			}
		}
	}
}
