.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


In addition:

* The recommended amount of RAM available to the |chef client| during a |chef client| run is 512MB
* The |chef client| binaries are stored in the ``/opt/chef`` directory, which requires a minimum of 200MB of disk space
* The |chef client| caches to ``/var/chef/cache`` during the |chef client| run. This is the location in which downloaded cookbooks, packages required by those cookbooks, and other large files are stored. This directory requires enough space to save all of this data and should be generously sized. 5GB is a safe number, as a starting point, but tune the size of ``/var/chef/cache`` as necessary
* Each node and workstation must have access to the |chef server| via HTTPS
* |ruby| 1.9.3 (or higher). In general, using the version of |ruby| that is installed by the |omnibus installer| is recommended
* The hosted |chef server| is compatible with |chef client| version 0.10.0 and greater; older clients must be upgraded before they can connect to |chef hosted|
