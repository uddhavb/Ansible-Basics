# HW5   
   
## Setup and Tasks:   
The ansible code for the given assignments in the setup and tasks sections are in the files **[setup](setup.yml)** and **[tasks](tasks.yml)** respectively.    

A **[screencast](https://youtu.be/yx4HeeMmK5o)** showing how to perform the setup and tasks along with the running app is also included in this repository.

##Steps for running ansible and playbook:
- Install ansible on the server machine.
```
ansible-box> $ sudo apt-add-repository ppa:ansible/ansible
ansible-box> $ sudo apt-get update
ansible-box> $ sudo apt-get install ansible
```   
- create an 'inventory' file that has a list of all the machines and their ip adresses and keys to be used by the ansible server to access them. The file may contain something like this.
`
[nodes]
192.168.33.100 ansible_ssh_user=vagrant ansible_ssh_private_key_file=./keys/node0.key
`
- Make a folder for keys and store the private keys of the nodes that will be accessed by the ansible server in seperate files. Store every file with a '.key' extension.
- run a change mode script `chmod 600 keys/nodeName.key` to give the necessary permissions to access the key files.
- running an ssh command should connect to the node machines. Something like this: `ssh -i keys/nodeName.key vagrant@192.168.33.20`
- Now run ansible commands on the anisble server. An example is `ansible all -m ping -i inventory -vvvv`
- Once ansible is set up, we can write ansible-playbooks to run ansible codes.
- The codes 'setup.yml' and 'tasks.yml' are ansible playbooks. We can run them by `ansible-playbook -i inventory setup.yml -s` command. Here it takes the inventory file as input which has all the nodes information. The -s gives sudo permissions if needed.
- On running this command we get the desired output and the respective changes are made to the node machines.


## Concepts:  
Answers to the **[concepts](concepts.md)** subsection of the homework.
