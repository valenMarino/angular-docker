# angular-docker

## Docker
### Create image
docker build -t angularfront -f Dockerfile .
### Run container
docker run -d -p 8081:80 --name angularapp angularfront
