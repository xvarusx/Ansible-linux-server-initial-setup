# Linux Server Initial Setup:

Ansible playbook that automatically configures a fresh Ubuntu or Debian server.

## Running Tests

Full bootstrap

```bash
  ansible-playbook bootstrap.yml
```

Only packages

```bash
  ansible-playbook bootstrap.yml --tags packages
```

Only security hardening

```bash
  ansible-playbook bootstrap.yml --tags security
```
