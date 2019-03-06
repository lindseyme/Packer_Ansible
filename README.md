# Packer_Ansible
Change and configuration management using Packer and Ansible.

## About the project
The simulations project was written in react/redux. The application is about a writing platform called AUTHORS HAVEN where different people express themselves through writing and also get an aundience for the written articles.

The script has been tested on AWS EC2 instance (ubuntu 18.04)

### Steps to take;
- Install packer and ansible;

`brew install packer`

`brew install ansible` 

- Git clone the repository

`https://github.com/lindseyme/Packer_Ansible.git`

- Create an AMI image on AWS.
- Add your AWS credentials to the variables.
- Run the packer script.

`packer build example.json`

- Run the ip address in the browser.
