#ALC (DevOps) Track Assessment

####Installation:

- Start up your terminal (or Command Prompt on Windows OS).

- Ensure that you've docker and docker-compose installed on your machine.

- Clone the DockerBuild App from the repo: https://github.com/popsyjunior/alc-devops-challenge with the command: 
	git clone https://github.com/popsyjunior/alc-devops-challenge
	
- Navigate to the project folder using:
	cd alc-devops-challenge
on your terminal (or command prompt)

- Clone the CRUD App from the repo: https://github.com/BolajiOlajide/UserManager
into **app/src** with the command: 
	git clone https://github.com/BolajiOlajide/UserManager app/src

- Run the command: 
	docker-compose up -d to spin up the docker containers in detatched mode.
- Run the command: 
	docker-compose ps
to check status of running containers.

- Use your API client (most commonly used is "postman") and test the endpoints as specified in the application documentation (with specified host port number).

#

###Author
**Popsana Barida** Software Developer.