# Ansible-create-user-and-exchange-ssh-key-with-hosts

U need to install ansible:</br>
<code>sudo apt install ansible</code>

Then:</br>
<code>ansible-playbook -i inventory playbook.yml -u username_to_login_ssh --ask-pass</code>
</br>
Now, if you have for example 10 machines and each one uses the same login credentials, for instance, root with the password root, then this script will log into each machine and create a user that you specify. It will also replace your SSH key so that you can log in automatically.
