# EU CAS
Experimental branch for testing out European Commission's CAS Authentication for Laravel 6-7.x.

This version of CAS, or Central Authentication Service, is experimental and should not be used for anything beyond testing.

This package offers and abstraction of [European Commission's CAS Lib](https://github.com/ecphp/cas-lib) (created by Pol Dellaiera), an open-source *CAS client* adhering to strict PHP's PSR coding standards.  

Check out the [wiki](https://github.com/subfission/cas/wiki) for further details.


## Updates
* Support added for Laravel 7.x
* Updated for Laravel 6.x
* Dropped support for PHP 5.x
* Laravel 5.5 Package Discovery support
* CAS logout method supports redirection service as a secondary argument
* Supports additional CAS versions, including version 1,2,3
* Supports direct phpCAS calls for heavily customized CAS configurations
* Supports logon with custom URL redirects
* Supports logoff with redirect callbacks
* Updated to work with Laravel 5.2 (backwards compatible)
* Uses the latest phpCAS
* Supports verbose logging
* Session handling has been removed from CAS Manager and is moved strictly into the middleware
* You can now leverage the CAS sessions instead of relying on Laravel sessions
* More security fixes
* Cleaner codebase
* Backwards compatible (for the most part)
* More configuration options in the config file available
* Masquerading as a user now supported
* Tested and working with PHP 7.x


