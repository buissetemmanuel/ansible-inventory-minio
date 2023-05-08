![LINT](https://github.com/buissetemmanuel/ansible-inventory-minio/actions/workflows/lint.yml/badge.svg) ![RELEASE](https://github.com/buissetemmanuel/ansible-inventory-minio/actions/workflows/release.yml/badge.svg)

INVENTORY MINIO to consume [ANSIBLE ROLE CONTAINER](https://github.com/buissetemmanuel/ansible-role-container.git)
=========

**MINIO** installation from scratch in cluster mode.

Goal
--------------

- manage packages if needed
- manage users if needed
- manage systems if needed
- 2 users include group and 1 group to access logs
- owner of files is not the user that manage systemd service
- manage 1 server or X server

Requirements
--------------
![ansible](https://img.shields.io/badge/ansible-2.12.3-green.svg)
![vagrant](https://img.shields.io/badge/vagrant-2.0.0-green.svg)

License
-------

[mit license]: https://img.shields.io/badge/License-MIT-blue.svg
[![mit license]](LICENSE)

Author Information
------------------

[email]: https://img.shields.io/badge/@-emmanuel@buisset.ch-orange.svg
[![email]](mailto:emmanue@buisset.ch)
