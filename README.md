# f5-lab

## Encrypt Vars

- Variables exist outside project `../credentials/creds.yaml
- Encrypt: `ansible-vault encrypt_string 'value' --name 'var'`
- Pass to Ansible: `ansible-playbook playbook.yaml --ask-vault-pass`
