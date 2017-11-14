# ACI setup with Ansible
A basic setup to automate ACI deployment with ansible.

The tasks folder contains a `main.yml` file which will execute some tasks among which:

1. Creates a ACI tennant.
2. Creates a physical domain.

## Usage

There are **three steps** required to run the ansible playbook:

 1. Clone the repository:
    
        git clone https://github.com/GaetanoCarlucci/ACI_setup_with_ansible.git

 2. Create the file `invertory.yml` based on the sample file `invertory_sample.yml`. Set the variables according to your setup.

 3. Within the **directory** run the command:
 
        :~/ACI_setup_with_ansible$ ansible-playbook -i inventory.yml site.yml -v
