# ansible
Infrastructure as code repository!

ssh-copy-id -i ~/.ssh/ansible.pub 192.168.x.x
ansible all -m ping
ansible-playbook install_docker.yml --ask-become-pass --limit ubuntu
