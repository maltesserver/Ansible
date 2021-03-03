# Ansible

Simple Ansible script for automatic installation of Tomcat with a webpage.
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



## Usage

```
ansible-playbook install-tomcat.yml

ansible-playbook remove-tomcat.yml
