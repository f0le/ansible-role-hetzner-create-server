Role Name
=========

Spins up a hetzner vps and optionally adds an ansible user with sudo privileges.

Requirements
------------

Setting up a project in Hetzner WebUI is needed, as well as an api-token and a ssh-key.

Role Variables
--------------

#TODO
 
add support for ansible vault 

--------------

Needed variables:

1. hcloud_token: $api_token
2. hcloud_server_image: $linux
3. hcloud_server_name: $myserver
4. hcloud_server_type: $type
5. hcloud_server_location: $seebelow
6. hcloud_server_ssh_keys: $ssh_key

For more information:

(https://docs.ansible.com/ansible/latest/collections/hetzner/hcloud/hcloud_server_module.html)

Hetzner location choices as of 02/2021:

1. fsn1 Falkenstein,DE
2. hel1 Helsinki, FI
3. nbg1 Nuremberg, DE

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

GPLv3

Author Information
------------------

[folie.dev](#https://folie.dev)
