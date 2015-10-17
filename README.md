# ansible-vault-helpers
Bash scripts for quick, easy use of Ansible Vault features

The ansible-vault-helper scripts assume your Ansible Vault password is in a file (outside of any public repo and only readable/writable by you) in your home directory, specifically, ~/.vault.

Scripts are intended to be somewhere in your path for convenience. Adding this repo to your path is highly recommended.

More on Ansible Vault at http://docs.ansible.com/ansible/playbooks_vault.html

avcreate: Creates Ansible Vault files

avdecrypt: Removes the encryption from Ansible Vault files (converts file to plaintext)

avedit: Decrypts file for use in your text editor (vim for Ansible Vaults)

avencrypt: Encrypts file using Ansible Vault

avview: Read-only view of an Ansible Vault file (less for Ansible Vaults)
