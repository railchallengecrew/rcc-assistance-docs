Reaction Roles
=================

reaction_role_create
--------------------

**Command:**
``reaction_role_create <STRING:embed_title> <STRING:embed_description> <CHANNEL:channel> <ROLE:role> <CHARACTER:emoji>``

**Permission required: Manage Channels**

Creates a new reaction role with the specified settings.

reaction_role_delete
--------------------

**Command:**
``reaction_role_delete <ROLE:role>``

**Permission required: Manage Channels**

Deletes the message to react with to access the role.

.. note::
    The role will not be deleted after running this command, and any
    users who have recieved the role will not be removed from the role.