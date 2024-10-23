## command for run ansible
```
ansible-playbook --ask-become-pass playbook.yml
```

## Ansible Basic command list
```
- ansible localhost/all/remote_server -m ping
- ansible-playbook file_name.yml
- ansible-playbook --syntax-check file_name.yml
- ansible-playbook -inventory --list
- ansible-config init --disabled > ansible.cfg
- ansible-galaxy init role-name
```