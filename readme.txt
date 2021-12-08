=== Add Twitter Cards ===

Description:	Add Twitter Cards to attach rich photos to Tweets, helping to drive traffic to your website.
Version:		1.4.2
Tags:			add-twitter-cards
Author:			azurecurve
Author URI:		https://development.azurecurve.co.uk/
Plugin URI:		https://development.azurecurve.co.uk/classicpress-plugins/add-twitter-cards/
Download link:	https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/download/v1.4.2/azrcrv-add-twitter-cards.zip
Donate link:	https://development.azurecurve.co.uk/support-development/
Requires PHP:	5.6
Requires:		1.0.0
Tested:			4.9.99
Text Domain:	add-twitter-cards
Domain Path:	/languages
License: 		GPLv2 or later
License URI: 	http://www.gnu.org/licenses/gpl-2.0.html

Add Twitter Cards to attach rich photos to Tweets, helping to drive traffic to your website.

== Description ==

# Description

Add Twitter Cards to attach rich photos to Tweets, helping to drive traffic to your website.

Options allow:
* Card Types of Summary or Summary With Images.
* Excerpt or first 200 characters of post added to card.
* Featured Image or first post image will be added to card (subject to configurable minimum size).
* Integrate with [Floating Featured Images](https:/development.azurecurve.co.uk/classicpress-plugins/floating-featured-image/) for card image.

This plugin is multisite compatible; each site will need settings to be configured in the admin dashboard.

== Installation ==

# Installation Instructions

 * Download the latest release of the plugin from [GitHub](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/latest/).
 * Upload the entire zip file using the Plugins upload function in your ClassicPress admin panel.
 * Activate the plugin.
 * Configure relevant settings via the configuration page in the admin control panel (azurecurve menu).

== Frequently Asked Questions ==

# Frequently Asked Questions

### Can I translate this plugin?
Yes, the .pot file is in the plugins languages folder; if you do translate this plugin, please sent the .po and .mo files to translations@azurecurve.co.uk for inclusion in the next version (full credit will be given).

### Is this plugin compatible with both WordPress and ClassicPress?
This plugin is developed for ClassicPress, but will likely work on WordPress.

== Changelog ==

# Changelog

### [Version 1.4.2](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.4.2)
 * Update azurecurve menu.
 * Update readme files.

### [Version 1.4.1](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.4.1)
 * Update azurecurve logo.
 
### [Version 1.4.0](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.4.0)
 * Add option to use featured image if one set, otherwise use existing functionality.
 * Fix bug with missing minimum image size check.
 * Fix bug with population of default options causing whitescreen.
 * Disable Use FFI option if [Floating Featured Image](https://development.azurecurve.co.uk/classicpress-plugins/floating-featured-image/) by [azurecurve](https://development.azurecurve.co.uk/) is not installed and active.

### [Version 1.3.4](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.3.4)
 * Fix bug with missing default options.
 * Update azurecurve menu.

### [Version 1.3.3](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.3.3)
 * Fix bug with population of default options.

### [Version 1.3.2](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.3.2)
 * Fix bug with incorrect language domain.
 * Update azurecurve plugin menu.
 
### [Version 1.3.1](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.3.1)
 * Remove unnecessary code from azrcrv_atc_get_option function.

### [Version 1.3.0](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.3.0)
 * Fix plugin action link to use admin_url() function.
 * Rewrite option handling so defaults not stored in database on plugin initialisation.
 * Add plugin icon and banner.
 * Update azurecurve plugin menu.

### [Version 1.2.0](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.2.0)
 * Add plugin icon and banner.
 * Add minimum dimensions for Twitter card image.

### [Version 1.1.5](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.1.5)
 * Fix bug with empty post array when getting twitter name.
 * Check size of image greater than 100px and search for next; if none found use fallback image.
 * Add unique id to Twitter card images as Twitter only allows one card to use a specific image.

### [Version 1.1.4](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.1.4)
 * Fix bug with setting of default options.
 * Fix bug with plugin menu.
 * Update plugin menu css.
 * Extend length of Twitter Username field.

### [Version 1.1.3](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.1.3)
 * Fix call of deprectaed get_usermeta to use get_user_meta.
 * Fix bug which prevented fall back image.
 * Rewrite default option creation function to resolve several bugs.
 * Upgrade azurecurve plugin to store available plugins in options.

### [Version 1.1.2](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.1.2)
 * Update Update Manager class to v2.0.0.
 * Update action link.
 * Update azurecurve menu icon with compressed image.

### [Version 1.1.1](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.1.1)
 * Fix bug with incorrect language load text domain.

### [Version 1.1.0](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.1.0)
 * Add integration with Update Manager for automatic updates.
 * Fix issue with display of azurecurve menu.
 * Change settings page heading.
 * Add load_plugin_textdomain to handle translations.

### [Version 1.0.3](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.0.3)
 * Fix bug with selection of image.

### [Version 1.0.2](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.0.2)
 * Fix bug with Twitter Card on non-singular pages.
 * Fix bug with text domain on addition of menu and rebuild pot.

### [Version 1.0.1](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.0.1)
 * Update azurecurve menu for easier maintenance.
 * Move require of azurecurve menu below security check.

### [Version 1.0.0](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/tag/v1.0.0)
 * Initial release; idea and some code from [Code Potent](https://codepotent.com/).

== Other Notes ==

# About azurecurve

**azurecurve** was one of the first plugin developers to start developing for Classicpress; all plugins are available from [azurecurve Development](https://development.azurecurve.co.uk/) and are integrated with the [Update Manager plugin](https://directory.classicpress.net/plugins/update-manager) for fully integrated, no hassle, updates.

Some of the other plugins available from **azurecurve** are:
 * Add Twitter Cards - [details](https://development.azurecurve.co.uk/classicpress-plugins/add-twitter-cards/) / [download](https://github.com/azurecurve/azrcrv-add-twitter-cards/releases/latest/)
 * Comment Validator - [details](https://development.azurecurve.co.uk/classicpress-plugins/comment-validator/) / [download](https://github.com/azurecurve/azrcrv-comment-validator/releases/latest/)
 * Contact Forms - [details](https://development.azurecurve.co.uk/classicpress-plugins/contact-forms/) / [download](https://github.com/azurecurve/azrcrv-contact-forms/releases/latest/)
 * Filtered Categories - [details](https://development.azurecurve.co.uk/classicpress-plugins/filtered-categories/) / [download](https://github.com/azurecurve/azrcrv-filtered-categories/releases/latest/)
 * From Twitter - [details](https://development.azurecurve.co.uk/classicpress-plugins/from-twitter/) / [download](https://github.com/azurecurve/azrcrv-from-twitter/releases/latest/)
 * Redirect - [details](https://development.azurecurve.co.uk/classicpress-plugins/redirect/) / [download](https://github.com/azurecurve/azrcrv-redirect/releases/latest/)
 * Tag Cloud - [details](https://development.azurecurve.co.uk/classicpress-plugins/tag-cloud/) / [download](https://github.com/azurecurve/azrcrv-tag-cloud/releases/latest/)
 * Theme Switcher - [details](https://development.azurecurve.co.uk/classicpress-plugins/theme-switcher/) / [download](https://github.com/azurecurve/azrcrv-theme-switcher/releases/latest/)
 * To Twitter - [details](https://development.azurecurve.co.uk/classicpress-plugins/to-twitter/) / [download](https://github.com/azurecurve/azrcrv-to-twitter/releases/latest/)
 * URL Shortener - [details](https://development.azurecurve.co.uk/classicpress-plugins/url-shortener/) / [download](https://github.com/azurecurve/azrcrv-url-shortener/releases/latest/)