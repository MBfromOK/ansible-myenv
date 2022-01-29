
# To Get a List of Playbook Tasks
``` shell
ansible-playbook -i inventories/hosts -K playbook1.yml --list-tasks
```

# To Run all Tasks in Playbook
```shell
ansible-playbook -i inventories/hosts -K playbook1.yml
```

# To Run task with a Specific Tag - Example: Minikube installation
```shell
ansible-playbook -i inventories/hosts -K playbook1.yml -t minikube
```
# TODO: Setup Vagrant from VSCode
# From: https://medium.com/@lizrice/ssh-to-vagrant-from-vscode-5b2c5996bc0e