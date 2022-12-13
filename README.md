# Simple-Ansible--Nginx-Install-to-two-Vagrant-VMs

# I have created the file "nginx-install.yml" under /etc/ansible and updated hosts file under /etc/ansible

# Then run "ansible-playbook nginx-install.yml -c local" command under /etc/ansible to install nginx into two Vagrant machines.

# I can check the command "ps -ef | grep nginx." whether nginx installed or not after running ansible-playbook command above. 

# Additionally, here is the command to ping all hosts "ansible all -m ping -c local"
