Homelab Ansible
===============

Automated setup of homelab systems

run playbook

```bash
ansible-playbook -K -i inventory.yaml <playbook>
```

restart cluster

```bash
ansible cluster -K -i inventory.yaml -a "reboot" -b
```

Shutdown cluster

```bash
ansible cluster -K -i inventory.yaml -a "shutdown -h now" -b
```
