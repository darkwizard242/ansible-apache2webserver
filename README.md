# ansible-apache2webserver
Contains `Ansible` playbooks to install or uninstall **Apache2** Web Server on RedHat (CentOS) & Debian(Ubuntu) systems.

## 1. Getting started:
This section contains steps to help in executing the playbooks.

### 1.1 Assumptions:
 * Ansible is installed on the controller node.
 * Python is installed on the controller node as well as all the nodes that you are managing with Ansible.
 * A user named `ansible` has been created on controller node and nodes you are managing. Passwordless SSH has been set up between them. If not ensure that it has been. If you are using a different user, then you will need to modify the `remote_user: ansible` keypair values to whichever user you have set up to use ansible on controller node and set up passwordless SSH with on all the nodes you are managing. For e.g. if your user for performing changes with Ansible is 'iamauser' then, change from `remote_user: ansible` to `remote_user: iamauser`
 
