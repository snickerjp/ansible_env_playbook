# Provisioning Ansible Env for Ubuntu 14.04

## Usage

```bash
cp hosts.template hosts
vi hosts
vi main.yml # replace snickerjp
cd /opt/idcf_ansible_playbook
ansible-playbook main.yml -i hosts -c ssh --ask-sudo-pass
```
