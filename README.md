# ansible

This repository contains all the basics and the project automation using `ansible`

What is a playbook ?

```
A Playbook is a list plays.
``` 

What is a play ?

```
A play is a list of taks ?
```

What is a task ?

```
A task can be anything that you wish to perform
```

A Playbook can be written using YAML and all the playbooks should end with `.yml` or `.yaml` 

PS : YAML is intendation specific. 



How to know the list of all the facts ?

```
ansible all -i hosts -m setup
```
**following command is default one to execuite shell based command**
ansible -i inv all -e ansible_user=centos -e ansible_password=DevOps -m shell -a "df -h"

ansible is a configuration managemt tool
