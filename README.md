# ansible-playbook-ELK
A playbook for setting up the ELK Stack + Filebeat

## Instructions
 
 1. Edit your Ansible hosts file ('/etc/ansible/hosts') and add an 'hostname' entry for the server you wish to install ELK on. You can of course name the host any way you want, this is just an example. 
 2. In the terminal on the machine hosting Ansible, clone this repo.
 3. Cd into the directory, and run:
 `ansible-playbook site.yml`
 
 The plays in the playbook will run on the target server, installing ELK and filebeat. 
 
[site.yml]: https://github.com/DanielBerman/ansible-elk-playbook/blob/master/site.yml
