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

## Testing

If you add new functionality, make sure to write appropriate tests as well.

To install all required test dependencies in a local development environment you can execute the following:

```bash
# If not existent
python3 -m venv env

source env/bin/activate

pip3 install --upgrade -r requirements.txt
```

Run all tests:

```bash
molecule test
```

## Author Information

Florian Köhler

## License

This project is under the MIT License. See the [LICENSE](LICENSE) file for the full license text.
