pipeline {
	agent any 
		stages {
			stage ('stage-2') {
				steps {
							sh "yum update -y"
							sh "yum install httpd -y"
							sh "echo 'This is Sudarshan Here' > index.html"
							sh "chmod 777 index.html"
							sh "cp index.html /var/www/html"
							sh "service httpd start"
							
						
						
						}
				
				
				}
			
			}
	}
