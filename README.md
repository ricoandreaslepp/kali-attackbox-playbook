# kali-attackbox-playbook
An [Ansible](https://www.ansible.com/) playbook for configuring a simple Kali attackbox.

Run with `ansible-playbook site.yml -i hosts --ask-pass --ask-become-pass -e 'hostvar=install'`

Replace `hostvar` value with `uninstall` for uninstallation.