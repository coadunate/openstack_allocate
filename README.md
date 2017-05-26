# openstack_allocate
Note that it is required that you source the openstack_admin_rc.sh so that the OS* variables are loaded.
sample playbook to access openstack and collect facts about VMs and allocate floating IPs. 
Note that in ansible.cfg that the default python was switched to /usr/local/bin/python, this may need to be changed to /usr/bin/python 
