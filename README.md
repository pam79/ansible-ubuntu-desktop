# Ubuntu Desktop Ansible Config
A set of Ansible roles for configuring Ubuntu lts (16.04 and above) desktop environment. It automates the installation and configuration of essential, good to have utility programs (can be customized if needed), and other tools that are meant for Software Development, DevOps and related.                                              

Git and Ansible are the only requirements.

### Install requirements
    $ sudo apt install git
    $ git clone https://github.com/pam79/ubuntu-desktop-ansible-config.git
    $ cd ansible-ubuntu-desktop && ./ansible-installer.sh

### Run the playbook in cwd
>Enter your sudo password when prompted

    $ ansible-playbook desktop.yml --ask-become-pass

### Availables roles
>All roles are disabled by default except _locales_ and _essentials_. Remove comment to enable them.
- locales
- essentials 
- adapta-theme
- java-openjdk
- zsh
