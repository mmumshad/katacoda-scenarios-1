Your Ansible Control Machine will be the node/host from where you are executing the Ansible commands and the remote machine will be your Ansible targets. The remote machines does not require any agents installed on them, for the Ansible Control Machine to perform its tasks.

## Task

From the previous task we were able to understand that we executed an ansible command to know the version of ansible installed. Hence, that makes the host the Ansible Control Machine. 

To identify the Ansbile remote machine that we would be using for our exercies, execute the command below which display the contents of the hosts file. From the output you would see **host01** which will be our target machine where we will automate tasks remotely from the Ansible Control Machine.

`cat /etc/hosts`{{execute}}
