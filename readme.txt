=== Taxonomy Switcher ===
Contributors: webdevstudios, sc0ttkclark, jtsternberg
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3084056
Tags: taxonomy, taxonomies, term, terms, category, categories, convert, converter, tag, tags, custom taxonomy, custom taxonomies, switch taxonomies
Requires at least: 3.5
Tested up to: 3.8.1
Stable tag: 1.0.0
License: GNU AGPLv3
License URI: http://www.gnu.org/licenses/agpl-3.0.html

Switch the taxonomy for all terms or only child terms of a specified parent term.

== Description ==

This plugin allows you to select your "From", and "To" Taxonomies, to convert all terms. Optionally select a parent term to limit terms to switch. Typing term names will do a live search of terms with the name you are typing AND possess child terms.

Plugin also has built-in support for [WP-CLI](http://wp-cli.org/). In the command line, type in `wp taxonomy-switcher` for instructions.

[Plugin is on GitHub](https://github.com/WebDevStudios/taxonomy-switcher). Pull Requests and Forks welcome.

### Notes

Please keep in mind, if parent term isn't set, it will default to zero, which will migrate *all* terms for that taxonomy to the new taxonomy.


== Installation ==

1. **Backup!**
2. Upload 'taxonomy-switcher' to the '/wp-content/plugins/' directory
3. Activate the plugin through the 'Plugins' menu in WordPress
4. Navigate to the 'Taxonomy Switcher' admin page. You'll find the menu item under the 'Tools' menu item on the left.
5. Select your "From", and "To" Taxonomies.
6. Optionally select a parent term to limit terms to switch. Typing term names will do a live search of terms with the name you are typing AND possess child terms.
7. Switch them!

== Frequently Asked Questions ==


== Screenshots ==

1. Admin page
2. Live-searching for a parent term

== Changelog ==

= 1.0.0 =
* Release

== Upgrade Notice ==

= 1.0.0 =
* Release
