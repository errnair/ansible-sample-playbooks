### Provisioning AWS EC2 Instances with Ansible  
  
#### Prerequisites:
- `boto`
- `python2.7+`
- `aws_secret_access_key`+`aws_access_key_id` needs to be created on AWS.
- A valid AWS Key-Pair.

#### How-To
 
- Run the playbook
```python
ansible-playbook -i inventory/hosts main.yml
```
- Expected Output
```python
PLAY [Create AWS resources] ***********************************************************************************************************

TASK [Create a security group] ********************************************************************************************************
ok: [localhost]

TASK [Create an EC2 instance] *********************************************************************************************************
changed: [localhost]

PLAY RECAP ****************************************************************************************************************************
localhost                  : ok=2    changed=1    unreachable=0    failed=0
```

####
