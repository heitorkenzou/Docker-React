## React and Docker

This project was created with <a href="https://github.com/facebook/create-react-app">created-react-app</a>

# About the project

Standard React application containerized by Docker 

## Prerequisites

Make sure you have already installed Docker. 
<code>docker -v</code>
if you don't have docker installed, run this: 
<code> sudo apt-get update</code><code> sudo apt-get install docker-ce docker-ce-cli containerd.io
</code>

## Running the project

```bash
# cloning the repository
git clone https://github.com/heitorkenzou/Docker-React.git
# entering the project folder
cd Docker-React
# build and run the container
docker-compose up -d --build

```

(if you receive this error: ERROR: Couldn't connect to Docker daemon at http+docker://localhost - is it running?

If it's at a non-standard location, specify the URL with the DOCKER_HOST environment variable.
run this: <code>sudo chmod 666 /var/run/docker.sock</code>)

go to <a href="http://localhost:8001">localhost:8001</a>
  
# Build With
  
 - React.js
 - Docker




