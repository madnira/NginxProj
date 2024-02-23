# Base Image
Alpine with Node js

# Image details
A simple html page with Hello Arin is built and placed in the www/data
The page runs on local broswer with port exposed against the container port of 80

# Docker run command in detach mode
docker run -d --publish 5001:80  --name <container_name> hellonginx:3.0

# Page looks like
<img width="433" alt="image" src="https://user-images.githubusercontent.com/7934564/224428625-b78f7675-a5e4-4de2-b98d-103bd4f96bee.png">
