=== Count All ===
Contributors: horvath.agoston
Donate link: 
Tags: counter, baby, count, age, sidebar, widget
Requires at least: 2.8
Tested up to: 5.6
Stable tag: 0.3

Very simple, highly customizable counter widget for showing difference in
days from a specified date and time.

== Description ==

Very simple, highly customizable counter widget for showing difference in
days from a specified date and time.  Allows HTML in title and body.  Can
count up and down.  Supports multiple instances.

Originally developed as a baby age counter, but can be used for any counting
job.

The options in the widget are:

* *Title* is the widget's title. It can contain HTML; its value is simply embedded into the resulting HTML page.

* *Content* is the widget content field. It uses the [DateInterval::format](http://www.php.net/manual/en/dateinterval.format.php)
function to format the field contents. You can use any field specifiers from
that function.  Its contents are also embedded into the resulting HTML page,
so over the %-tags, you are free to use any HTML you want.

* *Date* specifies the date we should count difference from. Since this
plugin simply calculates the difference between 'now' and the specified date
(in 24-hour days), it can be used for counting down, for dates in the
future, or counting up, for dates in the past.

You can have multiple instances of this widget, of course.

For an example usage, see the screenshots section.

== Installation ==

The plugin consists of a single .php file, so it's very easy:

1. Upload `count_all.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Start using it on the 'Widgets' submenu of 'Appearance'

== Upgrade Notice ==


== Frequently Asked Questions ==


== Screenshots ==

1. Widget configuration (observe multiple instances)
2. This is how it looks in browser

== Changelog ==

= 0.3 =
* Updated to PHP7

= 0.2 =
* Removed 'div' tag around content, allowing for more flexibility.

= 0.1 =
* Initial release
