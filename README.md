# Ansible Inventory: Test Inventory 1

Test inventory

## Requirements

None.

## Dependencies

None.

## Example Playbook

```yaml
- hosts: int,&node.1
  gather_facts: no
  tasks:
    - name: do something
      debug:
        msg: did something
```

## License

[MIT](./LICENSE)

## Author Information

Trevor Highfill ([@theque5t](https://github.com/theque5t))
