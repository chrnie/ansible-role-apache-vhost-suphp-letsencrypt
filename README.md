chrnie.apache-vhost-suphp-letsencrypt
=========

Installs apache suPHP with different users per vhost and letsencrypt for SSL Certificates.

Requirements
------------

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

    - hosts: webserver
      roles:
         - { role: chrnie.apache-vhost-suphp-letsencrypt }

License
-------

MIT

Author Information
------------------

Created in 2017 by Christoph Niemann, https://github.com/chrnie
