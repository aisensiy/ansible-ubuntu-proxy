Ansible ubuntu proxy
=========

为国内服务器创建代理。

Requirements
------------

有一个 ss server

Role Variables
--------------

见 `vars/main.yml`

```
ssserver: "ssserver_ip"
ssserver_port: 1984
ssserver_method: "aes-256-cfb"
ssserver_password: "123123"
```

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: docker
      roles:
         - role: ansible-docker-accelerate
           ssserver: "server"
           ssserver_port: 1984
           ssserver_method: "aes"
           ssserver_password: "123123"

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).