# Ansible Hello World

## Folder Structure

.

├── helloworld.yml → Playbook yml

├── config → Required packages for keeping your configuration files

├── inventory

    ├── dv1
            ├── group_vars
               ├── all.yaml  → Properties or env variables values
            ├── hosts

## Run Ansible with Inventory

```
ansible-playbook   helloworld.yml -i inventory/dv1
```
