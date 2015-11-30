# Provisioning Ansible Env for Ubuntu 14.04

## Usage

```bash
cp hosts.template hosts
vi hosts
ansible-playbook main.yml -i hosts -c ssh --ask-sudo-pass
```
