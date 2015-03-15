dotfiles role
=============

vim, ssh, zsh, screen dotfiles

Requirements
------------

Vim, ruby, rake, zsh

Role Variables
--------------

`user`

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: lukeorland.dotfiles, user: lukeorland }


Add it to your Ansible playbooks repository's `requirements.yml`:

```yaml
# requirements.yml

- src: https://github.com/lukeorland/ansible-role-dotfiles
  version: master
  name: lukeorland.dotfiles
```

Install by running: `sudo ansible-galaxy install -r requirements.yml`


License
-------

BSD

Author Information
------------------

https://github.com/lukeorland
