# AZURE-CICD-Deployment-with-Github-Actions

## Save pass:

ta0rW+JXf/LfkE2KBJgSdTVzi34436S+ACRAbqmA/


## Run from terminal:

docker build -t bappyapp.azurecr.io/mltest:latest .

docker login bappyapp.azurecr.io

docker push bappyapp.azurecr.io/mltest:latest


## Deployment Steps:

1. Build the Docker image of the Source Code
2. Push the Docker image to Container Registry
3. Launch the Web App Server in Azure 
4. Pull the Docker image from the container registry to Web App server and run 