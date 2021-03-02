# ansible-role-asterisk16
Auto install and deploy asterisk 16 on Debian or Ubuntu server

![License](https://img.shields.io/github/license/mach1el/ansible-role-asterisk16?color=blue&style=plastic) 

## Role Pathes

    ├── defaults
    │   └── main.yml
    ├── handlers
    │   └── main.yaml
    └── tasks
        └── main.yml
        
## Role Playbook
    
    ---
    - name: Auto deploy asterisk 16.
      hosts: localhost
      roles:
        - 'ansible-role-asterisk16'
