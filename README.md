# poc-deployment

Ansible

```bash
# POC Deployment
ansible-playbook deploy-poc.yml -i _inventories/poc.ini -e @_creds/poc.yml --vault-password-file ~/secret-poc.txt

# Ansible Vault
ansible-vault create _creds/poc.yml --vault-password-file ~/secret-poc.txt
ansible-vault edit _creds/poc.yml --vault-password-file ~/secret-poc.txt
```
