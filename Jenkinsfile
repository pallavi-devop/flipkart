pipeline {
	agent any
	
	stages {
	    stage('Checkout') {
	        steps {
			checkout scm			       
		      }}
		stage('Build') {
	           steps {
			  sh '/home/pallavi/Documents/GRRAS/apache-maven-3.8.7/bin/mvn install'
	                 }}
		stage('Deployment'){
		    steps {
			
			sh 'cp target/project4.war /home/pallavi/Documents/GRRAS/apache-tomcat-9.0.71/webapps'
	}
}}}
