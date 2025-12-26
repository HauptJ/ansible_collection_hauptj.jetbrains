Ansible Collection - hauptj.jetbrains
========================================
[![Molecule Test](https://github.com/hauptj/ansible_collection_hauptj.jetbrains/actions/workflows/molecule.yml/badge.svg)](https://github.com/hauptj/ansible_collection_hauptj.jetbrains/actions/workflows/molecule.yml)

This collection contains roles to install JetBrains IDEs. It also allows you to install plugins for those IDEs by passing a list of plugin IDs to the roles.  

This collection also contains the Android Studio role, which is not a JetBrains IDE, but is based on the same installer and plugin system.  

Contents
========

Roles
------
Role | Description | CI Status
--- | --- | ---
[hauptj.jetbrains.idea](./roles/idea/) | Install IntelliJ IDEA | [![Molecule test](https://github.com/hauptj/ansible_collection_hauptj.jetbrains/actions/workflows/ansible-role-idea.yml/badge.svg)](https://github.com/hauptj/ansible_collection_hauptj.jetbrains/actions/workflows/ansible-role-idea.yml)
[hauptj.jetbrains.clion](./roles/clion/) | Install CLion | [![Molecule test](https://github.com/hauptj/ansible_collection_hauptj.jetbrains/actions/workflows/ansible-role-clion.yml/badge.svg)](https://github.com/hauptj/ansible_collection_hauptj.jetbrains/actions/workflows/ansible-role-clion.yml)
[hauptj.jetbrains.pycharm](./roles/pycharm/) | Install PyCharm | [![Molecule test](https://github.com/hauptj/ansible_collection_hauptj.jetbrains/actions/workflows/ansible-role-pycharm.yml/badge.svg)](https://github.com/hauptj/ansible_collection_hauptj.jetbrains/actions/workflows/ansible-role-pycharm.yml)
[hauptj.jetbrains.android_studio](./roles/android_studio/) | Install Android Studio | [![Molecule test](https://github.com/hauptj/ansible_collection_hauptj.jetbrains/actions/workflows/ansible-role-android_studio.yml/badge.svg)](https://github.com/hauptj/ansible_collection_hauptj.jetbrains/actions/workflows/ansible-role-android_studio.yml)
[hauptj.jetbrains.goland](./roles/goland/) | Install GoLand | [![Molecule test](https://github.com/hauptj/ansible_collection_hauptj.jetbrains/actions/workflows/ansible-role-goland.yml/badge.svg)](https://github.com/hauptj/ansible_collection_hauptj.jetbrains/actions/workflows/ansible-role-goland.yml)
[hauptj.jetbrains.common](./roles/common/) | Common role for all JetBrains IDEs. Not intended to be used directly. | N/A

Click on the role to see the README for that role.  
