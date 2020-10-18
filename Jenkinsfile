pipeline {
	agent any
	stages {
		stage("Run the code!") {
			steps {
				sh """
					python3 calculator.py
				"""
			} //steps
		} //stage
		stage("Run unit test") {
			steps {
				sh """
				    pytest
				"""	
			} //steps
		}//stage
	} //stages
} //pipeline


