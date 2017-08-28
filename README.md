## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) postgresql_server

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-postgresql_server.svg?style=flat)](https://travis-ci.org/debops/ansible-postgresql_server)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--postgresql__server-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-postgresql_server/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.postgresql_server-660198.svg?style=flat)](https://galaxy.ansible.com/debops/postgresql_server)


[PostgreSQL](http://www.postgresql.org/) is a popular relational open
source database. This role can be used to install and manage a set of
PostgreSQL clusters on Debian-based systems. You can use
``debops.postgresql`` role to configure roles and databases on local or
remote PostgreSQL servers.

### Installation

This role requires at least Ansible `v1.9.0`. To install it, run:

```Shell
ansible-galaxy install debops.postgresql_server
```

### Documentation

More information about `debops.postgresql_server` can be found in the
[official debops.postgresql_server documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-postgresql_server/docs/).


### Role dependencies

- `debops.secret`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- [Maciej Delmanowski](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-drybjed) (maintainer) | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)
- Nick Janetakis | [e-mail](mailto:nick.janetakis@gmail.com) | [Twitter](https://twitter.com/nickjanetakis) | [GitHub](https://github.com/nickjj)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
