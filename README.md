# ansible for redmine3.4.2  

ansible of redmine  
https://blog.adachin.me/wordpress/archives/6306  

# OS
・Amazon Linux   
・CentOS6  

# Middleware  
・redmine v3.4.2  
・ruby v2.4.1  
・rails v4.2.0  
・bundler v1.15.4  
・gem v2.6.11  
・H2O v2.2.4  
・mysql 5.7   

※ DB is not provisioning  

# dry-run  
````
$ ansible-playbook --private-key=~/.ssh/xxx -i hosts -u ec2-user redmine-web01.yml --ask-sudo-pass --check
````

# run  
````
$ ansible-playbook --private-key=~/.ssh/xxx -i hosts -u ec2-user redmine-web01.yml --ask-sudo-pass
````
