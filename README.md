# mylab-master-ansible
Ansible role to configure the master node


## Installing

1) Install prerequisites: [mylab_node](https://github.com/troppens/mylab-node-ansible#installing)

2) Install this role:

```
# cd /etc/ansible/roles
# git clone https://github.com/troppens/mylab-master-ansible.git mylab_master
```


## Usage

Configure master node with defaults:
```
- hosts: master
  roles:
    - mylab_master
```
