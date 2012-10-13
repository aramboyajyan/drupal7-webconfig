# Drupal 7 web.config file

[Drupal 7](http://drupal.org/) web.config file for use on Windows servers.

The file includes two fixes:

- Fix default favicon rewrite rules. See [this](http://drupal.org/node/1041580) issue for more information.
- Force of www in front of the domain name to avoid duplicate content on search engines.

Tested on Windows Server 2008 and IIS 7.0. This web.config works for single and multi site installs.

See also [web.config for use with Boost module](http://github.com/topsitemakers/drupal7webconfigboost).

<hr>

By: [topsitemakers.com](http://www.topsitemakers.com).
