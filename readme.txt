=== WikioVote-Button ===
Contributors: ppfeufer
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=N8GNRQFTS3XKS
Tags: wikio, button, vote, blog
Requires at least: 3.1
Tested up to: 3.4
Stable tag: 2.1

This plugin will install a Wikio-Button, to promote your posts on wikio.

== Description ==

This plugin will install a Wikio-Button, to promote your posts on wikio, to your blog articles, pages, archives, categories and rss.

**Features**

* Easy to install.
* Panel for easy configuration.
* Config display locations (entries, pages, home page, archive, category).
* Config position in content (before, after, both, manual choice).
* Choose from different buttons.

**Note**

If you choose the position as "manual choice" you have to edit your template-file and add the following code at a position of your choice.
`&lt;?php if(function_exists('wikiovote_button')) { echo wikiovote_button(); } ?&gt;`

**Available Languages**

* English
* German

== Installation ==

You can use the built in installer and upgrader, or you can install the plugin manually.

**Installation via Wordpress**

1. Go to the menu 'Plugins' -> 'Install' and search for 'WikioVote-Button'
1. Click 'install'

**Manual Installation**

1. Upload folder `wikiovote-button` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Configure plugin in 'Wikio-Button' menu

== Screenshots ==
1. the settings menu

== Changelog ==

= 2.1 (29. 03. 2012) =
* Wikio is now a shoppingportal and Wikiolabs is now ebuzzing. So the buttons won't work anymore and this plugin can be uninstalled.

= 2.0.2 (09. 11. 2011) =
* Ready for WordPress 3.3

= 2.0.1 (21. 04. 2011) =
* Fix: Update Options link in plugin overview.

= 2.0.0 (20. 04. 2011) =
* New: added new Wikio Boost Buttons.
* New: added a little wikio-icon to settings link.
* Change: moved link to settings page to settings menu.
* Change: reduced database load.
* Update: german translation.

**IMPORTANT**
Please check the settings after this update.

= 1.4.3 (09.01.2011) =
* Fix: corrected HTML output (thanks to [Kai](http://kkoepke.de) for reporting)

= 1.4.2 (09.01.2011) =
* Fix: corrected loading of JavaScript after saving action.

= 1.4.1 (08.01.2011) =
* Update: JavaScript

= 1.4.0 (07.01.2011) =
* Add: German translation

= 1.3.4 =
* Fixed behaviour in Opera and Webkitbrowsers

= 1.3.3 =
* Fixed shortcode

= 1.3.2 =
* Fixed a little Javascript-Error

= 1.3.1 =
* Headlinetext in Setting corrected

= 1.3.0 =
* Adding administrative Site to Dashboard
* Upload to Wordpress-Plugindirectory

= 1.2.0 =
* Both Wikio-Buttons now available (Long-Version and Big-Version)

= 1.1.0 =
* HTML-Code corrected
* IDs are now unique

= 1.0.0 =
* Initial Relaese

== Frequently Asked Questions ==

For any questions use the comments in my article http://blog.ppfeufer.de/wordpress-wikiovote-button-plugin/

== Upgrade Notice ==

Just upgrade via Wordpress.
