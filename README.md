
# Inmail Devops

# Setup Instructions Ansible
```Ansible is a configuration management tool, similar to Chef and Puppet. It allows for          performing logical configuration of infrastructure components, such as servers and network     switches. The configuration files in this repository can act as a template for your own Ansible projects, in order to get you started quickly. Once you've customized the  configuration files then new servers can be configured quickly — excluding their network configuration.```

    virtualenv ~/ansible
    source ~/ansible/source/bin/activate
    pip install ansible

# Ansible playbook's execution for this Application

## Using this repository

```
cd ~
git clone https://github.com/abhinavnarra/adhoc_project.git
```

## To execute playbooks

Simply run the following commands

```
cd ~/adhoc_project/ansible/web/playbook/dev
# Run dev tasks
ansible-playbook dev.yml -vvv

# Run qa tasks
ansible-playbook qa.yml -vvv

# Run uat tasks
ansible-playbook uat.yml -vvv
```

    NOTE: The below instructions are compatable with ubuntu 18.04/18.x (Vagrant)(ubuntu/images/hvm-ssd/ubuntu-xenial-18.04-amd64-server)
