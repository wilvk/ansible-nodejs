NodeJS
======

Ansible role for installing nodejs from NodeSource RPMs

https://github.com/nodesource/distributions


Supported node versions
-----------------------

* 0.10.x
* 0.12.x
* 4.x
* 5.x
* 6.x

Requirements
------------

Currently only for CentOS 6 & 7. Pull requests are welcome.


Role Variables
--------------

* `nodejs_version: 4.5.0` a supported nodejs version
* `nodejs_global_packages: [ ]` names of global npm packages to install

Example Playbook
----------------

    - hosts: example
      roles:
      - role: advertine.nodejs
        nodejs_version: "6.4.0"
        nodejs_global_packages:
          - grunt-cli
          - clean-css

License
-------

MIT

Author Information
------------------

Rafał Michalski

