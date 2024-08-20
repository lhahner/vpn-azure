# vpn-azure
A cloud based openvpn vpn server. This project should be my entry into reverse engineering.
My first approach is to setup a openvpn server in the an azure virtual desktop. 
Afterwards I would also like to create a Docker container Image which can be pulled and used on every linux server.

# Setting up a Azure Virtual Desktop
First step might be to create an Azure Virtual Desktop.
If you are a student you get a 100$ Budget for 1 year in the Azure cloud.
I think this offering makes Azure really worth trying and lead to my decision to host the vpn server in an Azure cloud vritual desktop.

Besides the Azure Account you need to set up a Azure Virtual Desktop. This is basically a virtual Machine running in a cloud server.
I used the Linux Ubuntu 20.03 Server for this project, because I am more familiar with it. I recommend you to do also.
After you have created the virtual desktop, just connect to it my ssh.

# Install a openVPN Server on an Azure Virtual Desktop
1. `sudo apt install openvpn` on the Linux server.

# Plans for the future
## Get a more detailed view about the openVPN project
I will cover are more technical installation process. So I expect that I will get a more detailed
overview about the setup and the design of the application.

## Create a Docker Container Image for the openVPN
I want to create a Docker Container Image which will provide a out of the box finished configuration for
openVPN. Therefore I will need a CLI Userinterface/Application which reads the needed important from the user
and guides through the installation process.
