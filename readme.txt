=== Dismiss "Welcome Panel" Nag Dashboard Widget ===
Contributors: luciano-croce
Donate link: https://github.com/luciano-croce/
Tags: dismiss-welcome-nag, dismiss-welcome-widget, dismiss-welcome-dashboard, welcome, welcome-nag
Requires PHP: 5.2.4
Requires at least: 3.8
Tested up to: 5.0
Stable tag: trunk
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

dismiss welcome panel nag dashboard widget when is activated or if it is in mu-plugins directory automatically

== Description ==

Dismiss "<strong>Welcome Panel</strong>" nag, dashboard widget, when is activated, or automatically, if it is in mu-plugins directory.

Development for this plugin takes place at [GitHub](https://github.com/luciano-croce/dismiss-welcome-nag/) and [Travis CI](https://travis-ci.org/luciano-croce/dismiss-welcome-nag/).

= Tips =

A neat trick, is to put this single file dismiss-welcome-nag.php (not its parent directory) in the /wp-content/mu-plugins/ directory (create it if not exists) so you won't even have to enable it, and will be loaded by default, also, since first step installation of WordPress setup!

= Explanation =

This, is different from the other similar plugins, because uses the filter hook, and not the action hook. Filters should filter information, thus receiving information/data, applying the filter and returning information/data, and then used. However, filters are still action hooks. WordPress defines add_filter/remove_filter as "hooks a function to a specific filter action", and add_action/remove_action as "hooks a function on to a specific action".

= What is Welcome Panel? =

[Welcome Panel](https://codex.wordpress.org/Plugin_API/Action_Reference/welcome_panel/) is a dashboard widget experience for WordPress 3.5+

== Screenshots ==

1. Dashboard Widget Enabled - Screenshot 1 of 4
2. Dashboard Widget Dismissed - Screenshot 2 of 4
3. As single Plugin Enabled - Screenshot 3 of 4
4. As mu-plugins Enabled - Screenshot 4 of 4

== Changelog ==

= 1.0.1 =

*Release Date: November 07, 2017*

* Changed plugin name
* Changed plugin description
* Renamed plugin slug
* Renamed text domain slug
* Preemptive Support for WordPress 5.0-alpha
* Preemptive Support for WordPress 4.9.1-alpha
* Compatible with WordPress 4.9-RC2-42115 or later
* Make sure that plugin run only under WP 3.8+ or greater
* Make sure that plugin run only under PHP 5.2.4 or greater
* Updated some descriptions to reflect code changes
* Updated screenshots according new changes
* Updated readme.txt according new changes

= 1.0.0 =

*Release Date: December 12, 2013*

* First initial release of the plugin
* Use the filter hook and not the action hook
* Compatible with WordPress 3.8+ or greater
* Compatible with mu-plugins directory
* Compatible with 1st step installation setup
* Compatible with GlotPress translations
* Requires WordPress Version 3.8+ or greater
* Requires PHP Version 5.2.4 or greater

== Upgrade Notice ==

= 1.0.1 =

1st [UPDATE] WordPress 3.8+ to 4.8 ~ 4.9-RC2-42115 (Build 2017-11-07) Revised the first initial release code of the plugin - Security and Maintenance Release According WordPress 4.8.0 / 4.8.1 / 4.8.2 / 4.8.3 / 4.9-alpha / 4.9-beta1 / 4.9-beta2 / 4.9-beta3 / 4.9-beta4 / 4.9-RC1 / 4.9-RC2 / 4.9.1-alpha / 5.0-alpha
