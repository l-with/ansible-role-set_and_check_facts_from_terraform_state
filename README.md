# Ansible Role set and check facts from terraform state

set and chacks fact from terraform state


## Dependencies

The role depends on terraform and a backend configuration for terraform including the credentials (possibly set by environment variables).

## Role Variables

### `set_and_check_facts_from_terraform_state_required_vars`: `[]`

the list of variables to get from the terrform state

The variables are looked uo from the output in the terraform state.