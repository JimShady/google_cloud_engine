# Google Cloud Engine
Instructions for creating and connecting to Google Cloud VM

Create an instance: https://console.cloud.google.com/compute/

Use PuttyGen to create a public and private key.

Save the private key to local PC (Dropbox?)

Copy the public key

Go to the VM, edit, add SSH, and paste it into the box.

Change the end of it to be use. For example:

ssh-rsa nosenseinhere myemail@gmail.com

Start Putty , then connect with the IP of the remote machine, username: myemail@<ipaddress>. Go to SSH. Auth. Provide the key (Dropbox).
  
Connect !

# Get Jupyer running

Python and envs: https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-programming-environment-on-an-ubuntu-18-04-server

THIS SEEMS TO WORK WELL : https://jeffdelaney.me/blog/running-jupyter-notebook-google-cloud-platform/
