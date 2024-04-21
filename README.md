Ansible playbook for Fedora 40:

`sudo dnf install ansible ansible-collection-community-general`

Check:
`ansible-playbook -v -i inventory -C main.yml`

Run with:
`ansible-playbook -v -i inventory main.yml`
