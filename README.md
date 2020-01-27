# ansible
Dedicated repository for my own Ansible setup.

Commands for running setup:
1. `chmod +x ./install_roles.sh`
2. `./install_roles.sh`
3. `ansible-playbook --ask-become-pass -i hosts site.yml`

Environment variables:
`ROOT_PASSWORD_MYSQL="your_pass"`