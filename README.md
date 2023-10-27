# Fabric Deployment Using a Seed Node: Getting Started

## Introduction

Describes how to create/deploy first fabric  using  seed node.

#Steps

Use the following steps to bring up the container image and launch the Create Fabric interface:

1.Sign in to the seed node host as root or a user that can run sudo commands without being prompted for a password.

2.Download the datafabric_container_setup.sh script from GitHub. For example, download the script in its raw form by using the following wget command:
    wget https://raw.githubusercontent.com/mapr-demos/mapr-db-750-getting-started/main/datafabric_container_setup.sh

3.Modify the script so it is executable:
    chmod +x datafabric_container_setup.sh

4.Running the datafabric_container_setup.sh script requires sudo privileges.

5.Run the script to deploy the container for the Data Fabric image:
    ./datafabric_container_setup.sh

6.The script downloads the latest image. When the Docker image is running, you see the following output:

================
7.5.0-mapr-devdocker-container % ./datafabric_container_setup.sh
Please enter the local sudo password for <username>
Password:

latest: Pulling from maprtech/edf-seed-container
Digest: sha256:052f461d98b1d0b8251cd47bab71b42103e61aaaa33d31335d3ca60182f4a87e
Status: Image is up to date for maprtech/edf-seed-container:latest
docker.io/maprtech/edf-seed-container:latest
Developer Sandbox Container db555c1625bd is running..
services required for Ezmeral Data fabric are coming up
services required for Ezmeral Data fabric are coming up
services required for Ezmeral Data fabric are coming up

Client has been configured with the docker container.

Login to DF UI at https://<hostname>:8443/app/dfui to deploy data fabric
For user documentation, see https://docs.ezmeral.hpe.com/datafabric/home/installation/installation_main.html
================





