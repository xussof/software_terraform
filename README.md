software_terraform
=========

This role will install software_terraform software

Requirements
------------

All dependencies will appear on requirements.yml file

Role Variables
--------------

software_packages:
  - terraform
software_version:
  - 0.11.14

software_url: "https://releases.hashicorp.com/terraform/0.11.14/terraform_0.11.14_linux_amd64.zip"

Not defined yet. But in the future we could stage software version in here

Dependencies
------------

All dependencies will appear on requirements.yml file

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: xussof.software_terraform }

License
-------

BSD

Author Information
------------------
Made by @xussof
