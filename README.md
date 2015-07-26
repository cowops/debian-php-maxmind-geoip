Debian-GeoipcityDatabase
========================

Maxmind geoip database for PHP

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

license_key: ""

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: loranger.debian-php-maxmind-geoip, license_key: "" }

Tasks
-----

  - Download and extract [Maxming geoip](http://www.maxmind.com/fr/geolocation_landing) database

License
-------

BSD