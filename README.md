mapr-client
========

Install mapr-client.

Requirements
------------


Role Variables
--------------

```
mapr_cluster_name:
hive_metastore_host:
proxy_env:
  http_proxy: http://1.2.3.4:3128
  https_proxy: http://1.2.3.4:3128
```

Dependencies
------------


Example Playbook
-------------------------

```
- hosts: edge
  roles:
    - mapr_client
```

License
-------

MIT

Author Information
------------------

vgonzalez@mapr.com
