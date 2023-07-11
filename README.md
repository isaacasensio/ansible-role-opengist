Opengist 
=========

A self-hosted pastebin powered by Git.

This Ansible role installs Opengist as a Docker service.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

```
opengist_image: "ghcr.io/thomiceli/opengist:1.4"
```
The version of the docker image to run as a container.
```
opengist_host_config_path: /etc/opengist
```
Opengist configuration folder in the host machine
```
opengist_container_user: opengist
```
Opengist container username
```
opengist_host_port: 6157
```
Opengist host port

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - iasensio.opengist

License
-------

MIT

