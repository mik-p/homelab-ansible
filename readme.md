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

cluster ansible guys
--------------------
https://github.com/Bengreen/raspi-cluster-ansible
https://github.com/geerlingguy/raspberry-pi-dramble/blob/master/tasks/disable-swap.yml
https://github.com/techno-tim/ansible-homelab/tree/master/playbooks

NAS storage class
-----------------
ref - https://jonathangazeley.com/2021/01/05/using-truenas-to-provide-persistent-storage-for-kubernetes/
driver - https://github.com/democratic-csi/democratic-csi

printable cluster racks
-----------------------
https://uplab.pro/

other
-----
https://digimoot.wordpress.com/2020/04/12/freenas-pi-hole-virtual-machine-install/
