# Ansible

Simple Ansible script for automatic installation of Tomcat on a selected Server with a webpage.
Built with the Red Hat Ansible Automation Platform.

## Installation

### VMs 

* 2 VMs running CentOS, RHEL or Fedora
* One is the Host, one the is Server
* Change the IP in the hosts file to your IP

### Installing Ansible on RHEL, CentOS, or Fedora

On Fedora:

```
sudo dnf install ansible
```

On RHEL and CentOS:
```
sudo yum install ansible
```

### Other Stuff

* Make sure you have all the files on the Host Computer 
* Run the Command down below with the correct IP in the hosts file and Voila

## Usage

```
ansible-playbook install-tomcat.yml

ansible-playbook remove-tomcat.yml
