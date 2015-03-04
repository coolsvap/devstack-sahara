devstack-sahara
===============
Devstack and Sahara localrc

Prerequisites:
--------------
- DevStack setup requires to have 1 VM/ BM machine with internet connectivity.
- Setup a fresh supported Linux installation. (Ubuntu/Fedora/CentOs)
- Install Git

Steps
-----
Clone devstack
```
$git clone https://github.com/openstack-dev/devstack.git
```

Clone devstack-sahara
```
$git clone https://github.com/svashu/devstack-sahara.git
```

Copy localrc from devstack-sahara to devstack
```
$ cp devstack-sahara/localrc devstack

```

Modify the devstack/localrc for IP and password modifications

Deploy your Devstack

```
$cd devstack && ./stack.sh
```
