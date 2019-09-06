# ghichep_ansible

## 1. Zabbix:

- Run ansible Zabbix-agent without ansible-vault:

```sh
ansible-playbook -i hosts setup.yml
```

- Edit file hosts with ansible-vault

```sh
ansible-vault edit hosts
```

- Run ansible with ansible-vault:

```sh
ansible-playbook -i host setup.yml --ask-vault-pass
```

## 2. Chrony:


- Run ansible chrony without ansible-vault:

```sh

cd /etc/ansible

ansible-playbook -i hosts setup.yml
```