=== Plugin Name ===
Contributors: David Kobia
Donate link: 
Tags: ushahidi, crowdmap, maps, google maps
Requires at least: 2.5
Tested up to: 3.0.3
Stable tag: 0.5

Embed Ushahidi/CrowdMap reports with maps in your Wordpress Blog

== Description ==

Using the 'shortcodes' Wordpress feature, this plugin allows you to embed [Ushahidi](http://ushahidi.com/download "Ushahidi") or [CrowdMap](http://www.crowdmap.com "CrowdMap") reports in your wordpress blog simply by specifying the link to the report.

== Installation ==

1. Upload `ushahidipress` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Screenshots ==

1. Screenshot 1
2. Screenshot 2

== Changelog ==

= 0.5 =
* Added optional [width], [height] attributes. Example: [ushahidi height=200, width=200]http://my.ushahidi.com[/ushahidi]
* Fixed issues with adding multiple maps
* Fixed issue with map rendering before text

= 0.2.1 =
* Fixed url whitespace issue

== Upgrade Notice ==

= 0.2.1 =
Fixed url whitespace issue

== Usage ==

* `[ushahidi]http://www.zombiereports.com/reports/view/441[/ushahidi]` - inserts the report into your blog post.