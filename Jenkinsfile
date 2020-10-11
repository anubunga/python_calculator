pipeline {
	agent any
	stages {
		stage("Run the code!") {
			steps {
				sh """
					python calculator.py
				"""
			} //steps
		} //stage
		stage("Run unit tests") {
			steps {
				sh """
					python -m pytest
				"""
			} //steps
		} //stage
	} //stages
} //pipeline
