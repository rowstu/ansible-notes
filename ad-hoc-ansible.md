# Misc Ad-Hoc Commands

Get the installed version of RHEL:
```
ansible all -m setup -a 'filter=ansible_distribution*'
```
