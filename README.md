## Sample Ansible Playbooks

#### Phase - II

 
- **./provision\_ec2-v1/** - Quickly Provision an AWS EC2 instance using Ansible.
- **./wordpress-lamp\_v1** - LAMP installation + Wordpress installation.
  
  
#### Phase - I

- **./simple_playbooks/newuser.yml** - Used to create a new user on a remote server and enable passwordless authentication.  
- **./simple_playbooks/time\_and\_upgrade.yml** - Used to set the time on the remote server, then upgrade the packages on the remote server (||| to `yum update`).  
- **./simple_playbooks/change\_single\_hostname.yml** - Change the hostname permanently on a remote server.  
- **./simple_playbooks/install\_apache.yml** - Install Apache (httpd) webserver on a remote server.  
- **./simple_playbooks/install\_mysql.yml** - Install MariaDB on a remote server.  
- **./simple_playbooks/mysql_secure_installation** - To simulate `mysql_secure_installation` on a remote server.  
