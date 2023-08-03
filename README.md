*VMware has ended active development of this project, this repository will no longer be updated.*

CoreOS autofs
=============

This role installs a working autofs service into a CoreOS node

Role Variables
--------------

- coreos_autofs_etc: where to store the autofs maps
- coreos_autofs_install_dir: where to install autofs
- coreos_autofs_systemd: where to install the service file

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: coreos
      roles:
         - role: "sigma.coreos-autofs"

License
-------

Copyright (c) 2015 VMware, Inc.

SPDX-License-Identifier: MIT OR GPL-3.0-only

This code is Dual Licensed MIT or GPLv3
