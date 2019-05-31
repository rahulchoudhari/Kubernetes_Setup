Role Name
=========

A brief description of the role goes here.

Requirements
------------

Please update the group_vars/all/var.yaml for kuberentes version and pod ip range

Role Variables
--------------

None

Dependencies
------------

1. Check group_vars/all/var.yaml for correct version
2. Update host file with your server name, host should be passwordless sshable from your common server
3. At the end of playbook, you need run "kubeadm join --" command, output  provided by playbook

Example Playbook
----------------

    ansible-playbook -i host kube_install.yaml

License
-------

BSD

Author Information
------------------

Rahul Choudhari - https://www.linkedin.com/in/rahul-choudhari-3145776/
