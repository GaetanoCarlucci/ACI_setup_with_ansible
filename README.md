# ACI setup with Ansible
A basic setup to automate ACI deployment with ansible.

## Usage

There are **three steps** required to run the ansible playbook:

 1. Clone the repository:
    
        git clone https://github.com/GaetanoCarlucci/ACI_setup_with_ansible.git

 2. Create the file `invertory.yml` based on the sample file `invertory.yml.sample`. Set the variables according to your setup.

 3. Within the `ACI_setup_with_ansible` dir run the command:
 
        ansible-playbook -i inventory.yml site.yml




