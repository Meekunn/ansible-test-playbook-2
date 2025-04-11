# 🛠 Ansible Test Playbook

This repository contains a basic Ansible playbook for testing configuration variables like `domain`, `password`, and custom strings. It's great for learning and experimenting with Ansible's structure, roles, and variable management.

---

## 📁 Structure

ansible-test-playbook/
├── ansible.cfg
├── inventory.ini
├── playbook.yml
├── group_vars/
│ └── all.yml
└── roles/
└── config_test/
├── tasks/
│ └── main.yml
└── vars/
└── main.yml

---

## 🔧 Configuration

Before running the playbook, **edit `group_vars/all.yml`** to set your config values:

```yaml
domain: "example.com"
admin_password: "SuperSecret123!"
custom_string: "AnsibleIsCool"
```
