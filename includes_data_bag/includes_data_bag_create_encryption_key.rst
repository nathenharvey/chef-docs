.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

An encryption key can be created with a command similar to:

.. code-block:: bash

   $ openssl rand -base64 512 | tr -d '\r\n' > /tmp/my_data_bag_key

this will create a secret-key file located at `/tmp/my_data_bag_key`.
