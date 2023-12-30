# ansible-using-ansible-vault-tags
# Set password to encrypt file
ansible-vault encrypt /home/ansible/confidential

# Pass Vault secret as you run
ansible-playbook --ask-vault-pass /home/ansible/webserver.yml