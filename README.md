## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) nullmailer

[![Travis CI](http://img.shields.io/travis/debops/ansible-nullmailer.svg?style=flat)](http://travis-ci.org/debops/ansible-nullmailer) [![test-suite](http://img.shields.io/badge/test--suite-ansible--nullmailer-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-nullmailer/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.nullmailer-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/1564)

This role installs and manages
[nullmailer](http://untroubled.org/nullmailer/). nullmailer is a
sendmail/qmail/etc replacement MTA for hosts which relay to a fixed
set of smart relays. It is designed to be simple to configure, secure,
and easily extendable.

`debops.nullmailer` role can be used to install and manage
`nullmailer` configuration.


### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.nullmailer

### Documentation

More information about `debops.nullmailer` can be found in the
[official debops.nullmailer documentation](http://docs.debops.org/en/latest/ansible/roles/debops.nullmailer.html).


### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.


### Authors and license

`nullmailer` role was written by:
- Hartmut Goebel | [e-mail](mailto:'h.goebel@crazy-compilers.com) | [website](http://www.crazy-compilers.com)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project.
