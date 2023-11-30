# Building Docker image for the node js app

````shell
docker build -t express-test .
````

# Running the docker image

````shell
docker run -d -p 3000:3000 express-test
````