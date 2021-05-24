Ansible role to chrony .

### Example Playbook

```
- hosts:
  - servers
  - chrony
  roles:
    - { role: clay_wangzhi.chrony, when: "groups['chrony']|length > 0" }
```

> test tag 2.2
