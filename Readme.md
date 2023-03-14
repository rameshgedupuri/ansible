# Ansible command reference
***

### To skips the tags with build.
```
ansible-playbook -i inventory main.yml --skip-tags build
```
### To limit the execution to a particular host name web-server
```
ansible-playbook -i inventory main.yml --limit web-server --tags start
```
### Calling the roles using the main inventory.txt file:
```
ansible-playbook ./playbooks/apache.yml -i inventory.txt
```
### Calling the roles using the inventory file of inventories(environments)
```
ansible-playbook ./playbooks/apache.yml -i /Ansible/ansible/Ansible-roles/inventories/development/inventory.txt
```

### Creating an ansible role:
```
ansible-galaxy init mysql_db
```