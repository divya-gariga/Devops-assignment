Assignment 3:
1. build the two images Dockerfile.db and Dockerfile.web using following commands
$ docker build -f Dockerfile.db -t backend .
$ docker build -f Dockerfile.web -t frontend .

2. run containers
$ docker run -d --name db backend
$ docker run -d --name web -p 81:80 --link db:db frontend

3. view the e-commerce app in browser in port number 0.0.0.0:81 or localhost:81

Assignment 4:
1. navigate to project directory 
2. run command
 $  docker-compose up
 which will run containers 
3. view the e-commerce app in browser in port number 0.0.0.0:85 or localhost:85

