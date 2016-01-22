## Introduction
This repo is a ansible_playbook module for deploying   
yum-cron which do scheduled securtiy update

## Environment
OS: CentOS6.5-x86-64  
ansible: 1.9.4  
yum: 3.2.29-43.el6.centos.noarch   


## Usage
clone this repo to /etc/ansible  
```
cd /etc/ansible
ansible-playbook -i inventory/devenv site_dev.yml
```
