ansible-misc-modules
====================

Some small modules for ansible (http://ansible.cc)

For now, only the patch module is available

patch
======

Example: 

```

name: Patch some paramiko code
patch: patchfile=/tmp/critical.patch strip=1 basedir=/usr/share/pyshared/paramiko"

```

Prerequisites:

GNU patch installed
