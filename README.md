# Container App

A simple web page packaged in a Docker container, served by nginx.
This project is the starting point for deploying containers on AWS
(ECR and ECS), with the infrastructure built in Terraform.

## Run it locally

docker build -t container-app .
docker run -d -p 8080:80 --name my-app container-app

Then open http://localhost:8080
