.. _require-label:

Required Packages
====================================================================


DjNRO heavily depends on the following:

* Python (<3 & >=2.6)
* Django (>=1.2) - python-django
* memcached
* python-django-extensions
* python-mysqldb (If you wish to use MySQL as the DB backend)
* mysql-client-5.1
* python-ipaddr
* python-django-south (For database migrations). If you deploy MySQL >=5.5 and earlier versions of south (< 0.7.5), you are advised to upgrade to South >=0.7.5, as you may suffer from this `bug <http://south.aeracode.org/ticket/523>`_
* python-django-tinymce (Flatpages editing made easier)
* python-memcache (Yeap! You need that for Google maps locations caching)
* python-django-registration (User activation made easy)
* apache2 (We suggest apache with mod_rewrite enabled - use your preferred server)
* libapache2-mod-wsgi
* apache2-shibboleth : The server should be setup as a Shibboleth SP
* A mail server - Tested with exim

Django Social Auth
-----------------------------

User authentication via social media is carried out by the `python-django-social-auth <http://http://django-social-auth.readthedocs.org/en/latest/index.html>`_ python-django-social-auth package. If your distro includes it, then go via your distro installation.

In any case we have included python-django-social-auth as an application inside the djnro Django project.

Django Social Auth: Requirements - Dependencies
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
* python-django-social-auth

 *  OpenId support depends on python-openid

 *  OAuth support depends on python-oauth2 



    
