# workstation
Default configuration for my workstation with ansible

## Prepare Workstation

1. Install Ansible
```bash
sudo apt update && sudo apt install ansible -y
```

2. Apply the configuration
```bash
ansible-pull -U https://github.com/hnrazevedo/workstation.git site.yml
```

# License
GPLv3

# Author Information
Created by [Henri Azevedo](https://hazevedo.dev)