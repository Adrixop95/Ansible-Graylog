# Ansible Graylog
Simple ansible-playbook for Graylog installation for CentOS 8/RHEL 8 systems.

## Why did you write it?
I was actually bored and wanted to recall the structure of the ansible project.  

If you want to run this project at home, change the address of the target server in the main project directory in the file `hosts`. You should also change the variables in the configuration file `roles/graylog/vars/main.yml`.  

To run the solution, execute the command
```
$ ansible-playbook -i hosts site.yml
```

After starting the application will be available at the address provided by you, port 9000. Default login/password: `admin/password`. 

Requires Ansible to be installed to run (duh).