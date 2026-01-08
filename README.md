```
ansible-galaxy collection install community.general
ansible-playbook -K playbook.yml
```


on ubuntu, run with: `ANSIBLE_BECOME_EXE=sudo.ws ansible-playbook -K playbook.yml`