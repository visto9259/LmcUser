LmcUser ChangeLog
=======

V3.3.3
------------

* Fixed session storage name to be constant not dependent from used class.
* Added the ability to exchange the underlying hydrator for the user hydrator decorator.

V3.3.2
------------

* updated unit tests
* Travis reconfig

V3.3.1
------------

* Update README.md

V3.3.0
------------

* This release marks the move from the old organization namespace to the new one.

V3.2.0
------------
* Updated minimum PHP version to 7.3
* Updated deprecated method ClassMethods to ClassMethodsHydrator
* Updated PHPUNIT to latest version (v9)
* Fixed broken unit tests
* General updates to CI condfig (Travis) 

V3.1.0
------------

* Migration from Zend to Laminas.
All namespaces, files, config keys and other references to Zend or Zfc were updates to Lmc.

* Due the extensive refactoring, this release has significant backward breaking changes from v3.0
of the original Zfc component. However, as this release does not constitute new features, it remains
part of the 3.X major version.
