# Feed webapp microservice

This repo contains a webapp that allows to create feed and upload items. The webapp is usesa microservice architecture with lean services. The micro service application is made of two backend services, a reverse proxy and a frontend. The code is organized as following:

- backend-feed: endpoints for creating feeds and uploading files
- backend-user: endpoint for authenticati
- frontend: the frontend implemented with ionic
- reverseproxy: nginx reverse proxy
- eks: Kubernetes deployment files 
