# playbook-configure-fedora-laptop

Ansible playbook for configuring my Fedora Laptop

How to use :

```bash
sudo dnf install git
git clone https://github.com/Lootax/playbook-configure-fedora-laptop.git
cd playbook-configure-fedora-laptop
chmod +x init.sh
./init.sh
nano inventories/localhost/hosts
ansible-playbook playbook.yml -i inventories/localhost/ --connection=local
```
