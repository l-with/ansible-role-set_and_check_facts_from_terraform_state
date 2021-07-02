# Ansible Role set and check facts from terraform state

set and chacks fact from terraform state

## Dependencies

The role depends on terraform and a backend configuration for terraform including the credentials (possibly set by environment variables).

## Role Variables

### `set_and_check_facts_from_terraform_state_required_vars`: `[]`

the list of variables to get from the terrform state

The variables are looked up from the output in the terraform state.

### `set_and_check_facts_from_terraform_state_terraform_command`: `'terraform'`

the terraform cmd

This can be used for GitLab ci to set to `gitlab-terraform` or for specifying a terraform command by full path.
