# Deploy app with Ansible

Install a quiz app.
Tested for Ubuntu and Rocky linux.

## Example playbook

```yaml
- name: Install app - Role
  hosts: all
  roles:
    - install-app
```
