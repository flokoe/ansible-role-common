# Ansible flokoe.common role

A role which installs and configures most basic things I always need.

**Mostly for my personal use, so be careful if you want to use it too!**

## Installation

Using `ansible-galaxy`:

```bash
ansible-galaxy install flokoe.common
```

Using `requirements.yml`:

```yaml
- src: flokoe.common
```

## Requirements

None

## Dependencies

None

## Example Playbook

```yaml
---

- name: Playbook
  hosts: all

  roles:
    - flokoe.common
```

## Author Information

Florian Köhler

## License

This project is under the MIT License. See the [LICENSE](LICENSE) file for the full license text.
