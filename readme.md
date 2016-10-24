Nginx Setup for Opencast
========================

This script will do an Nginx deployment for Opencast.

Deploy/update Nginx:

1. Update hosts:

        cp hosts.template hosts
        vim hosts

2. Deploy Nginx

        ansible-playbook -k -K -i hosts opencast-nginx-setup.yml [--limit host-or-group]
