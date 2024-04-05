# unraid-ansible
Start of a collection of ansible playbooks to support Unraid. 

You will need to install python on the Unraid server using the excellent nerd scripts plugin. I run my playbooks from a remote instance, you can place an ssh key for ansible in /boot/config/ssh/root/.ssh/authorized_keys. 

Playbooks: 
- add_unraid_cert.yaml  
This playbook downloads a certificate bundle from a webserver that is protected with htaccess. I run this under a SWAG container on a seperate instance. 
