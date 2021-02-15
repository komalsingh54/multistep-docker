# Docker Demo
`npm install`

Build steps 
  `docker build -t <username>/<reponame>:<version> .`
 
See your images
  `docker images`

Run container
  `docker run -p <host-port>:<container-port> --name <any-container-name> -d <image-id>`

Execute any command inside container
  `docker exec -it <container-name/container-id>`
  
To stop the container
  `docker stop <container-name/container-id>`

To start the container
  `docker start <container-name/container-id>`
  
To restart the container
  `docker restart <container-name/container-id>`
 
To delete the container
  `docker rm <container-name/container-id>`
  
To delete the image
  `docker rmi <image-name/image-id>`
