# User Feed Microservice

This repository contains a webapp that allows to create feeds and upload items. The webapp uses a microservice architecture with lean services in aws using Elastic Kubernetes Service (Amazon EKS). The micro service application is made of two backend services, a reverse proxy and a frontend. The code is organized as following:

- backend-feed: endpoints for creating feeds and uploading files
- backend-user: endpoint for authentication
- frontend: the frontend implemented with ionic
- reverseproxy: nginx reverse proxy
- eks: Kubernetes deployment files 
