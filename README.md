# node-qrcode-docker

node-qrcode-docker is an open-source project that provides a simple way to generate QR codes using a web interface. It is built using Node.js and Docker.

## How does it work?

The project is built using Node.js and Docker. The Node.js server listens for requests on port 3031 and generates QR codes using the `qrcode` package. The Dockerfile installs the necessary dependencies and sets up the environment for the Node.js server to run.

## How to install  (Could use some help creating an install.sh script to make this easier)
```
docker run -d -p 3031:3031 --name nodeqrcode nodeqrcode

```
## Disclaimer 
The software is provided "as is", without any warranty of any kind. 
