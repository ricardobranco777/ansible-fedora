Ansible playbook for Fedora 42:

`sudo dnf install ansible ansible-collection-community-general`

Check:
`ansible-playbook -v -i inventory.yml -C main.yml`

Run with:
`ansible-playbook -v -i inventory.yml main.yml`


To install nmap from upstream:
```
ansible-playbook -v -i inventory.yml nmap.yml
sudo dnf versionlock add nmap
```
