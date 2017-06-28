gvm-dep-ubuntu
===============

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-gvm-dep-ubuntu.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-gvm-dep-ubuntu)

Install [gvm dependencies on Ubuntu](https://github.com/moovweb/gvm#debianubuntu).

> # This role is deprecated
>
> From the version 3.0.0, [suzuki-shunsuke.gvm](https://galaxy.ansible.com/suzuki-shunsuke/gvm/) supports to install build dependencies.

Requirements
------------

Nothing.

Role Variables
--------------

* gvm_dep_from_source: Whether install the dependencies to install go from source. The default is "no".
* gvm_dep_dep: The minimum dependencies.
* gvm_dep_build_dep: The dependencies to install go from source.

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - role: suzuki-shunsuke.gvm-dep-ubuntu
```

License
-------

MIT
