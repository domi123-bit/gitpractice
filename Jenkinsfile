pipeline {
	agent any

	stages {
	stage('Checkout') {
		steps {
			checkout scm
			}
		}

	stage('Build') {
		steps {
			echo 'Building application....'
		      }
		 }
	stage('Test') {
		steps {
			echo 'Running Tests.....'
		}
	}
	stage('Deploy') {
		steps {
			echo 'Deploying application.....'
			}
		}
	}
} 	
