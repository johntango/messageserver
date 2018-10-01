Your goal is to run the server in a Docker container.
You will need to write the file Dockerfile to build an  image with node.js installed. Remember Dockerfile will need to run npm in the container and run the command 
"node server.js" to start the server in the container. 
Notice the port server.js is running on

docker build . 
docker run -p 80xx:80xx -d test xxxx
