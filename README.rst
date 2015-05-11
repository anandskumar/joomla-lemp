Joomla over LEMP stack
========================================================

Joomla! is an award-winning Content Management System (CMS) for building websites as well as a 
Model-view-controller (MVC) Web Application Development framework. Features include page caching
to improve performance, RSS feeds, printable versions of pages, news flashes, blogs, polls, website
searching, and language internationalization

This appliance includes all the features in `TurnKey NGinx FastCGI`_,
and on top of that:

- Joomla 3.2 configurations:
    - Installed from upstream source code to /var/www/joomla
- SSL support out of the box.
- PHPMyAdmin administration frontend for MySQL (listening on port 12322 - uses SSL).
- Postfix MTA (bound to localhost) to allow sending of email (e.g., password recovery).
- Webmin modules for configuring Apache2, PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH, MySQL, phpMyAdmin: username **root**
-  Joomla: username **admin** 


.. _Joomla: http://joomla.org
.. _Nginx: http://nginx.org
.. _TurnKey Core: http://www.turnkeylinux.org/core
.. _PHPMyAdmin: http://www.phpmyadmin.net
