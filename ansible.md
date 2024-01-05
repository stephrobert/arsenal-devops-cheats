# Ansible

Ansible is an open-source software provisioning, configuration management, and application-deployment tool enabling infrastructure as code. It runs on many Unix-like systems, and can configure both Unix-like systems as well as Microsoft Windows.
https://docs.ansible.com/ansible/latest/index.html
#plateform/multiple #target/local-remote #cat/DevOps
% ansible, yaml, automation, configuration management, orchestration


## ansible - Check Syntax of a Playbook

```
ansible-playbook --syntax-check <playbook|playbook.yml>
```

## ansible - Run a Playbook

```
ansible-playbook <playbook|playbook.yml>
```

## ansible - Run a Playbook with a Specific Inventory

```
ansible-playbook -i <inventory_file|production> <playbook|playbook.yml>
```

## ansible - Run a Playbook with Verbose Output

(Use `-vvv` for more detailed output)

```
ansible-playbook <playbook|playbook.yml> -v
```

## ansible - Run a Single Task from a Playbook

```
ansible-playbook <playbook|playbook.yml> --tags "<tag|package>"
```

## ansible - Run a Playbook with Extra Variables

```
ansible-playbook <playbook|playbook.yml> --extra-vars "<variable|test>=<value|test>"
```

## ansible - List Hosts Affected by a Playbook

```
ansible-playbook --list-hosts <playbook|playbook.yml>
```

## ansible - Run a Playbook in Check Mode (Dry Run)

```
ansible-playbook --check <playbook|playbook.yml>
```

## ansible - Running Ad-hoc Commands on localhost

```
ansible <group_or_host|all> -m <module_name|ansible.builtin.setup> -a "<module_arguments|filter=ansible_*_mb>" -i localhost, -c local
```

## ansible - Encrypt a File with Ansible Vault

```
ansible-vault encrypt <file|my_vault.yml>
```

## ansible - Decrypt a File with Ansible Vault

```
ansible-vault decrypt <file|my_vault.yml>
```

## ansible - Edit an Encrypted File with Ansible Vault

```
ansible-vault edit <file|my_vault.yml>
```

## ansible - View an Encrypted File with Ansible Vault

```
ansible-vault view <file|my_vault.yml>
```

## ansible-inventory - List All Hosts

```
ansible-inventory --list
```

## ansible-inventory - Show Inventory in YAML Format

```
ansible-inventory --list --yaml
```

## ansible-inventory - Show Specific Host Details

```
ansible-inventory --host <hostname|vm>
```

## ansible-inventory - Graph of Inventory

```
ansible-inventory --graph
```

## ansible-inventory - Export Inventory to a File

```
ansible-inventory --list > <output_file|filename.json>
```

## ansible-inventory - Use a Custom Inventory Script

```
ansible-inventory -i <inventory_file|inventory.py> --list
```

## ansible-inventory - Display Inventory Variables

```
ansible-inventory -i <inventory_file|inventory.py> --vars
```
