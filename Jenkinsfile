pipeline {
	agent {
		labels 'generic'
	}
	stages {
		stage("Run the code!") {
			steps {
				sh """
					python3 calculator.py
				"""
			} //steps
		} //stage
		stage("Run unit tests") {
			steps {
				sh """
					python3 -m pytest
				"""
			} //steps
		} //stage
	} //stages
} //pipeline
