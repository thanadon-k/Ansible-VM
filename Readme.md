### run command for install library in master
```sh
ansible-playbook jenkins.yaml -i inventory.yaml --ask-pass
```

### run command for install library in test
```sh
ansible-playbook test.yaml -i inventory.yaml --ask-pass
```

### run command for install library in pre-prod
```sh
ansible-playbook pre_prod.yaml -i inventory.yaml --ask-pass
```