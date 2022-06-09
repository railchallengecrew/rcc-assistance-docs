Warnings
===============

warn
------------

**Command:**
``warn <USER:member> [STRING:reason]``

**Permission required: Manage Messages**

Warns the user after they have done something against the rules.
Warnings are logged and are viewable with :ref:`view_warns`.

unwarn
------------

**Command:**
``unwarn <USER:member>``

**Permission required: Manage Messages**

Removes a warning from a user's log. Useful for accidental warns.

view_warns
------------

**Command:**
``view_warns [USER:member``

**Permission required: Manage Messages**

If ``member`` is provided, view the user's warning history.
If ``member`` is not provided, view the last 5 warns.
