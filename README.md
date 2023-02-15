# Ansible role: eclipse-ide

Installs [Eclipse IDE](https://www.eclipse.org/ide/).

The `eclipse` command is incorporated into the alternatives system.

## Requirements

* Ansible >= 2.10


## Role Variables

**version**

    adrianjuhl__eclipse_ide__version: 2022-12

The version of eclipse to install.

## Dependencies

None.

## Example Playbook

```
- hosts: servers
  roles:
    - { role: adrianjuhl.eclipse_ide }

or

- hosts: servers
  tasks:
    - name: Install Eclipse
      include_role:
        name: adrianjuhl.eclipse_ide
```

## License

MIT

## Author Information

[Adrian Juhl](http://github.com/adrianjuhl)
