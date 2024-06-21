# kali-attackbox-playbook
An [Ansible](https://www.ansible.com/) playbook for configuring a simple Kali attackbox.

## Usage
For local usage cache a sudo token and run with `ansible-playbook playbook.yaml`. For remote hosts configure the hosts file and run `ansible-playbook playbook.yml -i hosts --ask-pass`.

Replace `hostvar` value with `uninstall` for uninstallation.
