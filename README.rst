A recipe to install open-vm-tools on Ubuntu, using chef
=======================================================

Assigning this recipe to a chef node (that is an Ubuntu machine) should get the
open-vm-tools package up and running.

Since the package requires some kernel-level stuff it is slightly more complicated than
simply installing a package in chef (which is trivial, obviously).

