k8s-master
=========

Setup of master k8s-node(s).

Requirements
------------

One or more master nodes with Kubernetes installed.

Role Variables
--------------

Variables are defined in defaults.

Dependencies
------------

ansible-galaxy collection install kubernetes.core

Example Playbook
----------------

time ansible-playbook k8s-master.yml

License
-------

BSD