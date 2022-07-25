Role Name
=========

Creates a systemd service to run the Prometheus elasticsearch-exporter as a
Docker container.

Requirements
------------

Docker, docker-py, and  systemd

Role Variables
--------------

See defaults/main.yml

Dependencies
------------

TODO: Add Docker deps

Example Playbook
----------------

    - name: Prometheus elasticsearch-exporter
      hosts: monitor
      become: yes
      roles:
        - { role: lmickh.elasticsearch-exporter }
      tags:
        - elasticsearch-exporter

License
-------

MIT
