=== Genesis Widget Column Classes ===
Contributors: keraweb
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=YGPLMLU7XQ9E8&lc=NL&item_name=Genesis%20Widget%20Column%20Classes&item_number=JWPP%2dGWCC&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted
Tags: genesis, bootstrap, column, grid, widget, sidebar, dynamik
Requires at least: 3.1
Tested up to: 4.8
Stable tag: 1.2.2

Adds Genesis column classes to widgets.

== Description ==

As easy as it gets. Add column classes to widgets with a select box, check whether the widget is the first, and save!

I've built this plugin for the Genesis Framework, though it will work with any theme that uses the (old) Bootstrap column classes.

= Filter: `genesis_widget_column_classes` =
Allows you to change the available column classes

**Parameters:** `array` Default column classes.  
**Return:** `array` Array of column classes.  

= Filter: `genesis_widget_column_classes_capability` =
Change the capability required to modify column classes.  
Since  1.2.2  

**Default:** `edit_theme_options`  
**Parameters:** `string` The default capability.  
**Return:** `string` The new capability.  

You can use these filters inside your theme functions.php file or in a plugin.

== Installation ==

Installation of this plugin works like any other plugin out there. Either:

1. Upload and unpack the zip file to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress

Or search for "Genesis Widget Column Classes" via your plugins menu.

== Screenshots ==

1. Widget admin view
2. Frontend example ( `one-third + first` | `one-third` | `one-third` )

== Changelog ==

= 1.2.2 =

*	Feature: new filter `genesis_widget_column_classes_capability`. Change the capability required to modify column classes.
*	Enhancement: Helper method to get the available column classes.
*	Enhancement: Fix CodeClimate coding standards issues.

Detailed info: [PR on GitHub](https://github.com/JoryHogeveen/genesis-widget-column-classes/pull/5)

= 1.2.1 =

*	Fixed code inspections from CodeClimate
*	Tested with WordPress 4.8

= 1.2 =

*	Compatibility with plugins that use the `widget_display_callback` hook
*	Remove duplicate classes if found
*	Update textdomain hook

= 1.1.4 =

*	Usage of the WP_Widget object for generating input names and ID's
*	Add filter `genesis_widget_column_classes` to add/modify available column classes
*	Tested with WordPress 4.6

= 1.1.3 =

*	Usage of a single instance of the class
*	Add support for translate.wordpress.org
*	Minor code standard fixes

= 1.1.2 =

*	Allow "first" class when no width is selected

= 1.1.1 =

*	Fix: constructor for PHP7

= 1.1 =

*	Make plugin object oriented (OOP)
*	Make "no genesis theme" nag dismissible
*	Code, format and security improvements

= 1.0.1 =

*	Some small improvements

= 1.0 =

*	Created from nothingness just to be one of the cool kids. Yay!

== Other Notes ==

You can find me here:

*	[Keraweb](http://www.keraweb.nl/ "Keraweb")
*	[GitHub](https://github.com/JoryHogeveen/genesis-widget-column-classes/)
*	[LinkedIn](https://nl.linkedin.com/in/joryhogeveen "LinkedIn profile")
