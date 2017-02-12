# OAuth

OAuth implements the OAuth classes for use with Backdrop and acts as a support
module for other modules that wish to use OAuth.

This module includes a slightly modified version of this [OAuth Client/Server
library](http://oauth.googlecode.com/svn/code/php)

OAuth Client flow:

The callback to be used is `/oauth/authorized/%` where `%` is the id of the
consumer used by the client. We need the id of the consumer to be able to find
the token correctly.

## Status

This is an incomplete Backdrop version of the Drupal contributed module version
7.x-3.3.

## Installation

Install this module using the official Backdrop CMS instructions at
https://backdropcms.org/guide/modules

Visit the configuration page under Administration > Configuration > Category >
OAuth (`admin/config/category/oauth`) and enter the required information.

## Current Maintainers

### For Drupal:
- [Juan Pablo Novillo Requena (juampynr)](https://www.drupal.org/u/juampynr)
- [Kyle Browning (kylebrowning)](https://www.drupal.org/u/kylebrowning)
- [James O'Beirne (jobeirne)](https://www.drupal.org/u/jobeirne)
- [Pelle Wessman (voxpelli)](https://www.drupal.org/u/voxpelli)
- [Hugo Wetterberg](https://www.drupal.org/u/hugo-wetterberg)

### Port to Backdrop:
- [Graham Oliver](https://github.com/Graham-72)

## Credits
The Drupal module has been sponsored by [Good Old](http://goodold.se) and
[Mindpark](http://mindpark.se).

### Supporting organizations
[Lullabot](https://www.drupal.org/lullabot) module maintenance.

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
