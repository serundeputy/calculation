SHARETHIS
---------------------

Sharethis places those "Share with..." icons/links on the content on your page.

Integration with the ShareThis social bookmarking utility on selected node types.

CONTENTS OF THIS FILE
---------------------

 - Introduction
 - Tested
 - Known Issues
 - Special Thanks
 - Requirements
 - Installation
 - Coming From Drupal?
 - Usage
 - License
 - Credits
 - Maintainers

The code for this project was based on the original share project for Drupal 5.x. The code for this project has been trimmed down to only work with the ShareThis system, and not require any additional modules to work properly.

Features

Customize your ShareThis code using the STAPI

Select node types you wish to display ShareThis module on

Choose to display in $teaser view or not

Choose to display the ShareThis link in either the $link items, or in the $node->content itself

Customize the weight of the ShareThis link if in $node placement

Uses the ShareThis jQuery plugin so the ShareThis servers are queried after page rendering

Place a ShareThis block anywhere on your site

Views integration

TESTED
-----

Simple working in Backdrop 1.1 -- placed in node/content area and shared via Twitter, placed in blocks/Layout area and shared via Gmail, altered look and feel in some config options and shared via Linkedin.

KNOWN ISSUES
---------------------

None critical for Backdrop yet.  Using a different way to append Sharethis than the theme_mymodule function in the original Drupal module until I/someone explains the theming system in Backdrop better than I understand it.

There are many, many options to this module and not all of them have been tested for Backdrop CMS yet.

REQUIREMENTS
------------

none

INSTALLATION
------------

Install this module using the official Backdrop CMS instructions at https://backdropcms.org/guide/modules


COMING FROM DRUPAL?
-------------------

Using a different way to append Sharethis to the page than the theme_mymodule function in the original Drupal module.

PERMISSIONS
------------

@todo


USAGE
-----

You need social media knowledge and probably social media accounts/API keys for this module to provide value.

LICENSE
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.

CREDITS
-----------

This module is based on the ShareThis module for Drupal, originally written and maintained by a large number of contributors, including:

- Rob Loach <https://www.backdrop.org/u/robloach>

MAINTAINERS
-----------

- seeking

Ported to Backdrop by:

 - biolithic <https://github.com/biolithic>
