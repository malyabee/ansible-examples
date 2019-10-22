# User creation with   vault example
This ansible project used to demonstrate how to use ansible-vault to encrypt variable file which contains  user name and password.

We used  "hello" as encrypted key for  ansible vault.
We can run the  user creation playbook using following command.
	
       
	ansible-playbook single_useradd.yml --ask-vault-pass
