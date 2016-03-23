Changelog
=========

Version 1.6.1
-------------

* Fixed breaking templates when using the cached template loader; content was shown multiple times.
* fixed support for parsing nodes from a custom template engine.
* Improve error messages for invalid template block names.

Version 1.6
-----------

* Added Django 1.9 support

Version 1.5
-----------

* Added Django 1.8 support

Version 1.4
-----------

* Added Django 1.7 support

Version 1.3
-----------

* Added Python 3 support

Version 1.2
-----------

* Support variable extends with defaults in templates, e.g. ``{% extends FOO|default:'base.html' %}``.

Version 1.1
-----------

* Fix Django 1.4 support

Version 1.0
-----------

* First release, based on the code of django-cms.
