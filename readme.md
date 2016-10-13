Nginx Setup for Opencast
========================

This script will do an Nginx deployment for Opencast.
To deploy/update Nginx run:

    ansible-playbook -k -K -i hosts opencast-nginx-setup.yml [--limit host-or-group]
