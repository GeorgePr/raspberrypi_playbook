# Raspberry Pi playbook
This playbook installs Docker, Zsh, rsync along with plugins and configuration files to my Raspberry Pi running Raspberry Pi OS 64-bit. It also serves as a template for Debian-based x86 environments.

## Installation
  
  1. Clone or download this repository
  2. Create a vault file with `ansible-vault create vault.yml` specifying the become password for the host you intend to run this on (the syntax is `deb0_become_pass: <your_password>`.
  3. Run the playbook using `ansible-playbook -i hosts main.yml --ask-vault-pass`
