# Ansible Role - nodejs

Install NodeJS on a system

Available on Ansible Galaxy: [pgkehle.nodejs](https://galaxy.ansible.com/pgkehle/nodejs)

## Tags for which sections to run
```yaml
init:           # Basic installation
```

## Examples

```yaml
- hosts: all
  roles:
    - { role: pgkehle.nodejs, flags: ['init'] }     
```

## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))

### References

* https://nodejs.org/en/download/package-manager/
* https://github.com/nodesource/distributions
