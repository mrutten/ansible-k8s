k8s-install
=========

Installs Kubernetes software.

Requirements
------------

Master- and worker hosts to install Kubernetes on.
Debian Bullseye's version of containerd is currently 1.4, which no longer works with Kubernetes 1.24+.
https://containerd.io/releases/#kubernetes-support
Containerd 1.6 is downloaded to overwrite 1.4.

Role Variables
--------------

Variables are defined in defaults.

Dependencies
------------

None.

Example Playbook
----------------

time ansible-playbook k8s-install.yml

License
-------

BSD
