.. snowflake Ops documentation master file, created by
   sphinx-quickstart on Sat Nov 19 12:26:29 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

===========================================
snowflake Ops: Welcome
===========================================

This is the snowflake Ops documentation.
It's targeted at an technical audience, mainly developers and sysadmins.
Marketing and contract related details are available on our `website <https://snowflakeops.ch>`_.

.. warning::  This document is for the development version 6 which is currently in alpha stage. The current main version is 5-0-stable.

Version 6
-------------------------------------------

We are using so called server generations,
based on a certain Debian release and tied to versions of further software like PHP, MySQL and so on.
This concept allows you to select the appropriate version depending on the application you use,
and also to switch to a newer generation in a planned way according to your needs.
Right now, you are looking at the documentation for the version 6:

.. list-table:: 
   :stub-columns: 1

   * - OS Release
     - Debian 9 (Stretch)
   * - Webserver
     - nginx 1.10
   * - Database
     - MariaDB 10
   * - PHP
     - PHP 7.0
   * - EOL
     - ~ May 2022

Switch to the documentation of other generations by using the versions selector below.

We got your back
-------------------------------------------

Do you struggle with some configurations, or can we advise you somehow?
We're here and happy to help.
If you have any questions, don't hesitate to contact us:

* Livechat (see below)
* `Slack <https://snowflakeops.slack.com>`_ (`Registration <https://slack.snowflakeops.ch>`_)
* E-Mail: `team@snowflakeops.ch <mailto:team@snowflakeops.ch>`_
* Phone: `058 255 00 22 <tel:+41582550022>`_

Open source
-------------------------------------------

We strongly believe in open source software.
While this documentation is released as open soure already (`GitHub Project <https://github.com/snowflakeOps/docs>`_),
we are working hard to publish our Puppet wrapper modules as well.
Checkout our `GitHub Organisation <https://github.com/snowflakeOps>`_ or `Twitter <https://twitter.com/snowflakeOps>`_ for updates.

This work is licensed under the `Creative Commons Attribution-ShareAlike 4.0 International License <http://creativecommons.org/licenses/by-sa/4.0/>`_.

.. toctree::
  :hidden:

  changelog
  server/index
  services/index
  development/index
  support
  faq

