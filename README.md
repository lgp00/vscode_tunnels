Ansible Project to install Vscode 1.74.3 with working tunnels for remote vms

🔗 https://tinyurl.com/lgp00vsctunnels

- ansible-playbook playbook.yml -K
- ansible-playbook -i inventory playbook.yml -K

[ it needs the -K because vscode doesnt execute as root ]