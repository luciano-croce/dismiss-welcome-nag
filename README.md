# Dismiss Welcome Nag
[![Build Status](https://travis-ci.org/luciano-croce/dismiss-welcome-nag.svg?branch=master)](https://travis-ci.org/luciano-croce/dismiss-welcome-nag)

Dismiss "<strong>Welcome Panel</strong>" nag, dashboard widget, when is activated, or automatically, if it is in mu-plugins directory.
* <strong>Tips</strong>: a neat trick, is to put this single file dismiss-welcome-nag.php (not its parent directory) in the /wp-content/mu-plugins/ directory (create it if not exists) so you won’t even have to enable it, and will be loaded by default, also, since first step installation of WordPress setup!
* <strong>Explanation</strong>: this, is different from the other similar plugins, because uses the filter hook, and not the action hook. Filters should filter information, thus receiving information/data, applying the filter and returning information/data, and then used. However, filters are still action hooks. WordPress defines add_filter/remove_filter as “hooks a function to a specific filter action”, and add_action/remove_action as “hooks a function on to a specific action”.
