Homelab Ansible
===============

Automated setup of homelab systems

run playbook

```bash
ansible-playbook -K -i inventory.yaml <playbook>
```

Shutdown cluster

```bash
ansible cluster -i inventory.yml -a "shutdown -h now" -b
```
