# What is this?
This is a Vagrant box running the ubuntu/xenial64 box.

It installs Ansible via pip.

An ansible_local provisioner executes a playbook.

Current contents of the playbook:
* Install JDK8 via apt
* Install Maven via apt

Need to add prior to running (possible infosec issues):
* settings.xml
* script to configure Maven archetype
