The world's first most hackable single-board server should also be the most secure; ansible-zimaboard makes easy work of that. 

About Zimaboard: https://www.zimaboard.com

CasaOS: https://www.casaos.io

This just wouldn't be complete without it's own OS for automation: https://github.com/paigeadelethompson/netcraveos_zimaboard

Quickstart
------------

- `pip install paramiko ansible`
- edit `production` inventory file, to specify your host ip(s)
- `ansible-playbook -i production -u casaos -k -c paramiko -C casaos_zimaboards.yml -K`
## NetcraveOS

- `git clone https://github.com/paigeadelethompson/ansible-zimaboard.git /opt/ansible-zimaboard` 
- `ansible-playbook /opt/ansible-zimaboard/netcraveos_zimaboards.yml`

License
-------

MIT

Author Information
------------------

Paige Thompson <paige@paige.bio>


## Wiki 

https://github.com/paigeadelethompson/ansible-zimaboard/wiki/TODO
