### To test the ansible servers
``` 
ansible-playbook -i hosts.ini ping.yaml
```

### To copy the softwares to ansible servers
``` 
ansible-playbook -i hosts.ini copy.yaml
```

### To extract the softwares on ansible servers
``` 
ansible-playbook -i hosts.ini extract.yaml
```

### To deploy mq clustering
```
ansible-playbook -i hosts.ini mq.yaml 
```

### To undeploy mq clustering

```
ansible-playbook -i hosts.ini mq-delete.yaml 
```