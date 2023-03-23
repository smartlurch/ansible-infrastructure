This is a set of ansible playbooks to build up my home infrastructure

initially I am testing with ubuntu lxc containers on top of proxmox

the configure playbook sets up the ubuntu system:
1. installs packages
2. adds bash aliases
3. installas and configures docker/docker compose
4. creates docker-user for running containers
	a. initially the docker-user password is 'password' but must be changed on first login

the deploy playbook deploys containers using docker-compose on the remote system

*NOTE: see TODO.md for work to be done*


*based on the work of Ironicbadger*
