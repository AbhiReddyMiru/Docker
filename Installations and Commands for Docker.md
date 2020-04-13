# INSTALLATION OF DOCKER ON WINDOWS

## NOTE:
*	Before installation turn of Hyper-v in windows feature 
*	During installation check the 

### Commands For Docker 

	docker --version : to check the verion of the docker
	docker run hello-world: To run docker image
	docker ps / docker ps -a: to check status of processor of container
	docker container ls -all: To list out all the containers
	docker rm : To remove container
	docker rm $(docker ps -a -q -f status=exited) : to remove all the containers which are exited
	docker image ls : To list all the docker images
	docker run -it -d ubuntu
