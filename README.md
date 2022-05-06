# Ansible Role - nodejs

Install NodeJS on a system

Available on Ansible Galaxy: [isaackehle.nodejs](https://galaxy.ansible.com/isaackehle/nodejs)

## Tags for which sections to run

```yaml
init: # Basic installation
```

## Examples

```yaml
- hosts: all
  roles:
    - { role: isaackehle.nodejs, flags: ["init"] }
```

## Linting

```bash
yamllint -c yamllint.yaml .
ansible-lint .
```

## License

MIT

## Author Information

Isaac Kehle
@isaackehle ([twitter](https://twitter.com/isaackehle), [github](https://github.com/isaackehle), [linkedin](https://www.linkedin.com/in/isaackehle))

### References

- [NodeJS Package Manager](https://nodejs.org/en/download/package-manager/)
- [NodeSource Distributions](https://github.com/nodesource/distributions)
