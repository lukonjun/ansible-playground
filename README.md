# ansible-playground
Ansible adhoc command with ping
```
ansible all -m ping -i hosts.ini
```
import public role
```
ansible-galaxy install geerlingguy.docker
```
Run Playbook
```
ansible-playbook copy_remote_remote.yml -i hosts.ini
```