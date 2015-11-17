# Ansible-deployment
Using Ansible to deploy a new application on a remote server

This is a real life example modified (to remove anything proprietary) to show you how to minimally work with a remote system in Ansible.

You can learn from this example and then create your own Ansible playbook.

The configuration is easy:
main.yml is your playbook and will use the following files:
- downloadupload.iap.yml - download a .gz file from a URL
- backup.iapsettings.yml - backup existing configuration files on the remote server
- deploy.iap.yml - deploy the application (in this case a JAR) and fire up services

Hopefully you will get a sense as to how easy this is to work with (Ansible). You can create your own playbook (main.yml and /tasks) to do fun and useful administration work.
