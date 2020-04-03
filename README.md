zsh ansible role
=========
This role installs zsh, zprezto and sets up a custom propmt

Requirements
------------
None

Role Variables
--------------
This role requires the following variables to be defined elsewhere in the playbook that uses it:
```yaml
    zprezto_dir:          /usr/local/share/zprezto  # zprezto install dir
    admin_user:           admin                     # Default admin user
```

Dependencies
------------
None


Example Playbook
----------------
Register the role in requirements.yml:
```yaml
    - src: capitanh.zsh_ansible_role
      name: zsh
```
Include it in your playbooks:
```yaml
    - hosts: servers
      roles:
      - zsh
```

License
-------

BSD

