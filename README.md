# Ansible Project for Installing Vscode 1.74.3 💻

This Ansible project provides a simple and convenient way to install Vscode 1.74.3 on your remote VMs and set up working tunnels for remote development.

## Complete Installation ☑️

To perform a complete installation, including downloading and installing Vscode and setting up the tunnel, run the following command:

```bash
ansible-playbook -i inventory complete_playbook.yml -K
```

## Installation Only 📦

If you only need to install Vscode 1.74.3 without setting up the tunnel, run the following command:

```bash
ansible-playbook -i inventory 1_install_vscode_1.74.3.yml -K
```

## Start/Restart the Tunnel 🔁

To start or restart the Vscode tunnel, run the following command:

```bash
ansible-playbook -i inventory 2_start_tunnel_vscode.yml
```

## Stop the Tunnel 🚫

To stop the Vscode tunnel, run the following command:

```bash
ansible-playbook -i inventory 3_stop_tunnel_vscode.yml
```

**Note:** The -K option is necessary for some commands that need root access, but not for all.

## Contributing 🤝

We welcome contributions to this project! If you have any suggestions or improvements, please feel free to create a pull request.

## License 📄

This project is licensed under the MIT License.
