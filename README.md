# ubuntu-base Ansible Role

This role does a few basic things to a vanilla Ubuntu 14.04 install:

- sets the timezone
- upgrades the kernel
- installs some commonly used utilities such as httpie and jq.
  See `tasks/install_utilties.yml` for a full list
