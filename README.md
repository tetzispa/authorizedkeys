# authorized_key


```yml
git clone https://github.com/tetzispa/authorizedkeys.git

ansible-galaxy install -r requirements.yml
```
Change remote_user and hosts in playbook.yml
```yml
ansible-playbook -i inventory.ini  playbook_ssh_keys.yml -K -k
```

