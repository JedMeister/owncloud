ownCloud - Share files, music, calendar
=======================================

`ownCloud`_ helps store your files, folders, contacts, photo galleries,
calendars and more on a server of your choosing. Access that folder from
your mobile device, your desktop, or a web browser. Access your data
wherever you are, when you need it.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- ownCloud Server:
   
   - Installed from official zip file. No automatic updates.

- SSL support out of the box.
- `Adminer`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Apache2, PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL: username **root**
-  Adminer: username **adminer**
-  ownCloud: username **admin**


.. _ownCloud: http://owncloud.org/
.. _TurnKey Core: https://www.turnkeylinux.org/core
.. _Adminer: http://www.adminer.org
