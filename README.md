# Ansible: nodejs

Install NodeJS on a system

Available on Ansible Galaxy: [pgkehle.nodejs](https://galaxy.ansible.com/pgkehle/nodejs)

## Tags for which sections to run
```yaml
install:        Install nodejs packages
port_enable:    Run the `setcap` command to allow the process to open a port
```

## Examples

```yaml
- hosts: all
  roles:
    - { role: pgkehle.nodejs, tags: [ 'install', 'port_enable' ], when: (vm_client_type == 'gui') }
```

## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))


## For local development testing

```bash
rsync -av ~/code/ansible-nodejs/* ~/.ansible/roles/pgkehle.nodejs
```


### References

* https://nodejs.org/en/download/package-manager/
* https://github.com/nodesource/distributions
