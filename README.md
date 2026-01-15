Create ansible.cfg.file and modify to give inventory file path.

ansible.cfg can be created under playbook folder or one below it. In the absence of this file, ansible will use default cfg file path at /etc/ansible/ansible.cfg

Entries under "/inventory/hosts" file can be hostnames (if DNS resolvable) or IP addresses
