=== Plugin Name ===
Contributors: twodayslate
Donate link: http://zac.gorak.us
Tags: categories, widget, sidebar
Requires at least: 4.0
Tested up to: 5.0.3
Stable tag: 5.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Show your site's most recently used categories!

== Description ==

Widget to display your site's most recent categories. 

Current options:

 * Max number of categories to display
 * Title
 * Display date
 * Icon (if set by [Simple Cateogry Icon](https://wordpress.org/plugins/simple-category-icons/))
 * Display post count

GitHub: https://github.com/twodayslate/Recent-Categories-Widget

== Installation ==

Enable the widget in the sidebar

1. Upload `widget.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Place `<?php the_widget('Recent_Categories_Widget'); ?>` in your templates
4. Or add the widget to your dynamic sidebar in the dashboard (Appearance -> Widgets).

== Frequently Asked Questions ==

= What options are there? =

You can set the max number of categories to show, the title, display icon, and the date.

= How can I contribute? =
Feel free to submit an issue or a pull-request on [GitHub](https://github.com/twodayslate/Recent-Categories-Widget).

= What is the best way to contact you? =
Check out [my website](http://zac.gorak.us) for a list of ways to do just that!

== Screenshots ==

1. screenshot-1.png widget shown in sidebar of Twenty Fifteen

== Changelog ==

= 1.0 =
* Initial Release

= 1.1 =
* Added support for [Simple Cateogry Icon](https://wordpress.org/plugins/simple-category-icons/)

= 1.2 =
* Rewrite
* Added post count option

= 1.3 =
* Added before_title and after_title support
* Bug fixes

== Upgrade Notice == 

= 1.0 =
First release. 

= 1.1 = 
If you want icon support it is recommended that you upgrade. 

= 1.2 =
Rewrite to add post count option

= 1.3 = 
n/a