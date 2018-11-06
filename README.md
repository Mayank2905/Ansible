# Ansible
# All file in the repository will run from the Ansible master server where ansible is installed 

# File: instance.yaml
Description: running this file using ansible-playbook instance.yaml -vvv will create the 2 instances automatically 
Note : inside instance.yaml file aws_access_key: Axxxxxxx aws_secret_key: P1sCxxxx is dummy as you need to change it according to your AWS access pairs.

 In the git repository there are two folder specific for 2 instance MSR-test-Instance-1 and MSR-test-Instance-2 with there own dependency

# MSR-test-Instance-1 :
inside this folder you have main.yaml
this file has the whole cconfiguration from installing dependency mention in the assignment
NVM – Version 0.33.2
Node – 8.12.0
Docker – 18.06 or latest
Docker Compose – 1.13 or latest
Openssl – latest version
Git – latest version
# and than building docker image for webserver and hosting the website
 

# MSR-test-Instance-2 :
inside this folder you have main.yaml
this file has the whole cconfiguration from installing dependency mention in the assignment
 NVM – Version 0.33.2
 Node – 8.12.0
 Docker – 18.06 or latest
 Docker Compose – 1.13 or latest
 Openssl – latest version
 Git – latest version
# and than building docker image for CouchDB and hosting the website on Futon


