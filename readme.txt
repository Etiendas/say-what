=== Say what? ===
Contributors: leewillis77
Donate link: http://www.leewillis.co.uk/wordpress-plugins/?utm_source=wordpress&utm_medium=www&utm_campaign=say-what
Tags: string, change, translation
Requires at least: 3.5
Tested up to: 4.0
Stable tag: 1.2

== Description ==
An easy-to-use plugin that allows you to alter strings on your site without editing WordPress core, or plugin code. Simply enter the current string, and what you want to replace it with and the plugin will automatically do the rest!

The plugin's available for forking and contribution over on [GitHub](https://github.com/leewillis77/say-what)

== Installation ==

* Install it as you would any other plugin
* Activate it
* Head over to Tools &raquo; Text changes and configure some string replacements

Note: This plugin may produce performance issues if you use it to configure a *large* number of string translations. I'd be interested in feedback if that's the case.

== Frequently Asked Questions ==

= Can I use it to change any string? =
You can only use the plugin to translate strings which are marked for translation.

= How do I find the string to translate? =
You can either have a guess, or checkout the plugin in question's source code, translatable strings are generally wrapped in __(), _e(), or _x(), for example:

`$foo = __('This is a translatable string', 'plugin-domain');`

== Screenshots ==

1. Finding a string to replace
2. The admin screen - setting up a replacement
3. The result


== Changelog ==

= 1.2 =
Swap database to UTF-8 to fix problems entering non-ASCII strings.

= 1.1 =
Fix incorrect escaping on the admin screens.

= 1.0.1 =
Fix initial DB table creation
Fix translations for strings with no domain

= 1.0 =
Allow strings with context to be replaced

= 0.9.3 =
Documentation improvements

= 0.9.2 =
Avoid wpdb->prepare warning
Minor admin fixes, don't double translate strings

= 0.9.1 =
Fix issue with fields being swapped when first entered

= 0.9 =
Beta ready for testing and feedback
