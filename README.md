Building out an Ansible Playbook Covering different RHCSA TOPICS
Using pretty much only the ansible built in shell for the plays.


Basic ls -l on the target server users home dir
ansible-playbook -i hosts.ini inventory/plays.yml --ask-become-pass
