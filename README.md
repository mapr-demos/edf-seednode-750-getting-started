# Fabric Deployment Using a Seed Node: Getting Started

## Introduction

Describes how to create/deploy first fabric  using  seed node.

#Steps

Use the following steps to bring up the container image and launch the Create Fabric interface:

1.Sign in to the seed node host as root or a user that can run sudo commands without being prompted for a password.

2.Download the datafabric_container_setup.sh script from GitHub. For example, download the script in its raw form by using the following wget command:
     
     wget https://raw.githubusercontent.com/mapr-demos/edf-seednode-750-getting-started/main/datafabric_container_setup.sh

3.Modify the script so it is executable:
     
     chmod +x datafabric_container_setup.sh

4.Running the datafabric_container_setup.sh script requires sudo privileges.

5.Run the script to deploy the container for the Data Fabric image:
     
     ./datafabric_container_setup.sh

6.The script downloads the latest image and once the docker image is up and  running, details of url using which  fabrics can be deployed will be printed on console

## Documentation Link
For user documentation, see https://docs.ezmeral.hpe.com/datafabric/home/installation/installation_main.html






