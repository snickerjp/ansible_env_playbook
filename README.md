# Provisioning Ansible Environment for Ubuntu 14.04

## Usage

### for remote host
```bash
cp hosts.template hosts
vi hosts
vi main.yml # replace snickerjp
ansible-playbook main.yml -i hosts -c ssh --ask-sudo-pass
```

### for localhost
```bash
cp hosts.template hosts
vi main.yml # replace snickerjp
ansible-playbook main.yml -i hosts -c local --ask-sudo-pass
```

### Vagrant for localhost
```bash
cp vagrant.yml.template vagrant.yml
vi vagrant.yml # replace vars:
ansible-playbook vagrant.yml -i hosts -c local --ask-sudo-pass
```

