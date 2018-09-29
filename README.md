letsencrypt
===========

Install and configure letsencrypt facility

Role Variables
--------------

```yaml
letsencrypt_domain_name: YOUR_DOMAIN_NAME
```

Dependencies
------------

- pylabs.nginx

Example Playbook
----------------

```yaml
  roles:
    - role: pylabs.letsencrypt
  vars:
    letsencrypt_domain_name: www.example.com
```

License
-------

MIT

Author Information
------------------

William Wu
