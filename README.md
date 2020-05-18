# notejamwa
Note Jam web app

# Commiting code to this Github repository will trigger a build of the Docker Container and a push to the Azure Container Registry (notejamwa.azurecr.io)


# A task is created in this container registry that automates the rebuild of the container
# A webhook is created in this container registry that deploys the container to the Azure Web App (for containers): https://webjamwa.azurewebsites.net