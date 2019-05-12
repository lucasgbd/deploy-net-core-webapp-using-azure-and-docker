# deploy-net-core-webapp-using-azure-and-docker
Deploy .NET Core WebApp using Azure and Docker

Running a Container
$ docker build -t webapp .

docker run -d -p 5000:80 --rm --name webapp webapp 19c758fdb9bfb608c4b261c9f223d314fce91c6d71d33d972b79860c89dd9f15

verify that the container is running using the docker ps command.

open a browser and go to the URL http://localhost:5000/

