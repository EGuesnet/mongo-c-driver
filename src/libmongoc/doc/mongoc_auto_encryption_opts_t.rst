:man_page: mongoc_auto_encryption_opts_t

mongoc_auto_encryption_opts_t
=============================

Options for enabling automatic encryption and decryption for `Client-Side Field Level Encryption <https://docs.mongodb.com/manual/core/security-client-side-encryption/>`_.

Synopsis
--------

.. code-block:: c

  typedef struct _mongoc_auto_encryption_opts_t mongoc_auto_encryption_opts_t;

See Also
--------

* The guide for :doc:`Using Client-Side Field Level Encryption <using_client_side_encryption>`

.. only:: html

  Functions
  ---------

  .. toctree::
    :titlesonly:
    :maxdepth: 1

    mongoc_auto_encryption_opts_new
    mongoc_auto_encryption_opts_destroy
    mongoc_auto_encryption_opts_set_key_vault_client
    mongoc_auto_encryption_opts_set_key_vault_namespace
    mongoc_auto_encryption_opts_set_kms_providers
    mongoc_auto_encryption_opts_set_schema_map
    mongoc_auto_encryption_opts_set_bypass_auto_encryption
    mongoc_auto_encryption_opts_set_extra

