# Ansible

add host: ssh-copy-id user@pc

ansible-playbook astra-update.yaml -K

ansible all -a "rm -f pam_mount.conf.xml warn=false" -K -b
