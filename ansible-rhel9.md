# Notes and gotchas

User RHEL9 Ansible core no longer includes stuff you took for granted. Therefore you have to manually install them from Galaxy

```
ansible-galaxy collection install ansible.posix
Starting galaxy collection install process
Process install dependency map
Starting collection install process
Downloading https://galaxy.ansible.com/api/v3/plugin/ansible/content/published/collections/artifacts/ansible-posix-1.5.4.tar.gz to /root/.ansible/tmp/ansible-local-321260iyd24ek2/tmpx119trm1/ansible-posix-1.5.4-vgouxgd6
Installing 'ansible.posix:1.5.4' to '/root/.ansible/collections/ansible_collections/ansible/posix'
ansible.posix:1.5.4 was installed successfully
```
