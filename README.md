![Ansible Lint](https://github.com/johanneskastl/ansible-role-cilium_sysctl_override_rp_filter/workflows/Ansible%20Lint/badge.svg)

cilium_sysctl_override_rp_filter
=========

Create a sysctl override file to set `net.ipv4.conf.lxc*.rp_filter` required by Cilium.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: 'johanneskastl.cilium_sysctl_override_rp_filter'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
