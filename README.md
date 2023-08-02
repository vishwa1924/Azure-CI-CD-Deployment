AZURE-CICD-Deployment-with-Github-Actions
Save pass:
vPR02UVhwBnoqxQ3bOhxAqqQ0ZqdKwDOUnllP4LK1s+ACRCeZfew

Run from terminal:
docker build -t flasksimpleapp.azurecr.io/mltest:latest .

docker login flasksimpleapp.azurecr.io

docker push flasksimpleapp.azurecr.io/mltest:latest

Deployment Steps:
Build the Docker image of the Source Code
Push the Docker image to Container Registry
Launch the Web App Server in Azure
Pull the Docker image from the container registry to Web App server and run