Setup-RedHat7-mirror
=========
Ansible playbook for local Red Hat 7 mirror.

Requirements
------------
Ansible server:
- Ansible 2.7+

Target machine(s):
- SSH connection with the sudo access.
- libselinux-python (for SELinux config on RHEL)
- Red Hat 7 machine
- Valid Red Hat account with related subscription access
- Internet access to https://cdn.redhat.com (for packages download)
- Internet access to https://subscription.rhsm.redhat.com (for registration and id_pool attach)
- Partition with 200GB free space (for a packages download)

What is missing 
--------------
Setup https for the mirror.

Example Playbook
----------------
`ansible-playbook -i hosts.inv setup-rhel7-mirror.yml -u linux_username -k -K`

License
-------
No license, use it as you wish.

Author Information
------------------

Darko Drazovic \
LinkedIn: https://www.linkedin.com/in/darkodrazovic \
Personal: https://darkodrazovic.in.rs \
Blog: https://kompjuteras.com \
GitHub: https://github.com/kompjuteras
