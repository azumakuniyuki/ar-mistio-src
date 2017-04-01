Ansible Role: mist.io(src)
================================================================================
Build and install the community edition of mist.io on your CentOS 7.

Requirements
--------------------------------------------------------------------------------
No requirements.

Role Variables
--------------------------------------------------------------------------------
The following variables are defined in `defaults/main.yml` file.
```
mistio:
  version: master
  started: true
  rebuild: false
  install: /usr/local/mist.io
  updateonly: false
  workingdir: /usr/local
  repository: https://github.com/mistio/mist.io.git
  config:
    address: 127.0.0.1
    port: 8000
```

Dependencies
--------------------------------------------------------------------------------
None

Example Playbook
--------------------------------------------------------------------------------
```yaml
- hosts: servers
  roles:
     - azumakuniyuki.ar-mistio-src
```

License
--------------------------------------------------------------------------------
BSD

Author Information
--------------------------------------------------------------------------------
[azumakuniyuki](http://nyaan.jp/)

