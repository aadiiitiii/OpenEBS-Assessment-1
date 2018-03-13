# OpenEBS- Assessment-1

STEPS->

1. First you need to clone the repo or else download it as a zip file.

2. Go to that folder via terminal.

3. Just check if python-pip is installed or not.

	To install it on Ubuntu: sudo apt-get install python-pip
	
	To install it on Fedora: dnf install python-pip

4. Use the kuberctl to apply the .yaml files.

	1. kubectl apply -f pods.yaml 
	2. kubectl apply -f deployment.yaml 
	3. kubectl apply -f services.yaml

5. Run the docker file. 

	docker run -e user-name="aditi" -p 127.0.0.1:80:80 aadiiitiii/openebs1:ver1
	
	Enter your name here "aditi"

6. A link will get displayed which will contain the required output.
