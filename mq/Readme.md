### To test the ansible servers
``` 
ansible-playbook -i hosts.ini ping.yml
```

### To copy the softwares to ansible servers
``` 
ansible-playbook -i hosts.ini copy.yml
```

### To extract the softwares on ansible servers
``` 
ansible-playbook -i hosts.ini extract.yml
```

### To deploy mq clustering
```
ansible-playbook -i hosts.ini mq.yaml 
```

### To undeploy mq clustering
```
ansible-playbook -i hosts.ini mq-delete.yaml 
```