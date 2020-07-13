# This Ansible role installs an HTTPD on Centos or RedHat.

Run this role by : $ansible-playbook run-role.yaml -i inventory

Notes:
- Don't forget to create your own inventory file for the tagted hosts that required to have httpd service.
- For first time you run the role , choose install action and ignore the second prompt with any input.
- for Upgrading to latest version , choose Upgrade and ignore the second prompt with any input.
- for Downgrading , choose downgrade and then answer the second prompt with the specific version of httpd pacackge. 
- You can modify the configuration for httpd from the templates only without modifiying anything in the tasks 





