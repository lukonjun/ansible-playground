# ansible-playground
Ansible adhoc command with ping
```
ansible all -m ping -i hosts.ini
```
Ansible adhoc command with command
```
ansible master -m command  -a "kubectl get nodes" -i host.ini
```
import public role
```
ansible-galaxy install geerlingguy.docker
```
Run Playbook
```
ansible-playbook copy_remote_remote.yml -i hosts.ini
```
Run a Playbook from a certain position
```
ansible-playbook kubernetes-installation.yml -i ../hosts.ini --start-at-task="Move keadm bin"
```
