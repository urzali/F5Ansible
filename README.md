# F5ConfigSync
Config Sync from the most updated F5 Redundanct peer
Ansible script that is going to Sync configuration from the peer device that has most recent changes.

This script involves SSH logins to remote F5s and has been tested from RHEL unit.
To authenticate using Shared Keys, copy over local ssh public key from /root/.ssh/id_rsa.pub to remote F5 at .ssh/authorized_keys
(If the local machine does not have ssh keys generated, generate them by using command "ssh-keygen -t rsa")

Make sure to modify "hosts" file under "inventory" to specify BigIPs included in the script.
Default inventory file should be at /etc/ansible/hosts (path is by default specified under /etc/ansible/ansible.cfg file)


