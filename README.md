# Ansible-create-user-and-exchange-ssh-key-with-hosts

U need to install ansible:
<code>sudo apt install ansible</code>

Then:
<code>ansible-playbook -i inventory playbook.yml -u username_to_login_ssh --ask-pass</code>
