# ansible-role-basic [![Build Status](https://travis-ci.org/hugomrdias/ansible-role-basic.svg?branch=master)](https://travis-ci.org/hugomrdias/ansible-role-basic)
> Role to do basic setup in Debian systems

This is for advanced users.

## Requirements
None   

## Role Variables
Check `defaults/main.yml` and `vars/main.yml` for dependencies default vars

## Dependencies
run `ansible-galaxy install -r tests/roles.yml -p tests/roles`
- tersmitten.locales

## Resources

https://github.com/jnv/ansible-role-unattended-upgrades   
https://wiki.debian.org/UnattendedUpgrades

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: hugomrdias.basic }

## License
MIT © [Hugo Dias](http://hugodias.me)
