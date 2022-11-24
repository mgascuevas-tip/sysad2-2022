## 1. How to create an Ansible Configuration.
You can have your default configuration file in the default path directory in /etc/ansible/hosts or you can create one just by creating a new file 
with custom configurations due to the fact that there are certain settings in Ansible that can be change via a configuration file (ansible.cfg). The stock
configuration found in that directory should be sufficient for most of us beginning to learn about ansible.

## 2. How to create an Ansible Inventory
Before you create your inventory you must have your playbook plugin, because without it your inventory cannot be read by running it or having your own JSON/YAML file.
A playbook needs to be run with a number of command-line flags when there is no inventory. Additionally, there isn't a significant efficiency gain from applying 
a playbook to a single device as opposed to doing the same thing manually.

## 3. How to create an Ad-hoc Ansible command with setup and shell module.
If you are running to virtual machines, you can use any cloud environment of your choice whether through a network or a controller. The VMs that you are using
will be the hosts in which we control through Ansible. The Ansible controller should be able to connect to the VMs by using SSH connection. Lastly, all you need is
the ansible configuration file and this controls all the Ansible ad-hoc commands that you are trying to execute.
