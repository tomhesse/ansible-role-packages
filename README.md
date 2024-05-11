# Ansible Role: Packages

Manages packages with apt.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see defaults/main.yml):

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
        - tomhesse.packages
      vars:
        packages:
          - vim
          - curl
          - htop

## License

MIT

## Author Information

This role was created in 2024 by [Tom Hesse](https://www.tomhesse.xyz).
