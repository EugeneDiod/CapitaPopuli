CAPITA POPULI (aka. capuli)
==========================

La démocratie bourgeonne en ce printemps 2011.

INSTALLATION
------------

Run the following scripts:

 * `bin/vendors.sh` (use `--min` if you don't want all the history)
 * `bin/build_bootstrap.php`
 * `app/console assets:install web/`


CONFIGURATION
-------------

Check that everything is working fine by going to the `web/config.php` page in a
browser and follow the instructions.

Copy `parameters.dist.ini` to `parameters.ini` in `app/config/` and input your configuration.

Make sure `app/cache` and `app/logs` are readwrite by php.