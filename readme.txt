=== Far Future Expiry Header ===
Contributors: Tips And Tricks HQ
Donate link: http://www.tipsandtricks-hq.com/wordpress-far-future-expiration-plugin-5980
Tags: cache, expiry header, far future expiration, expires header, wp-cache, minify, gzip, javascript, css, compression,
Requires at least: 3.5
Tested up to: 3.8.1
Stable tag: 1.2
License: GPLv2 or later

This plugin will add a far future expiry header for various file types to improve page load speed.

== Description ==
This plugin will modify your .htaccess file by inserting code which will add expires headers for common static file types.

Expiry header specifies a time far enough in the future so that browsers won't try to re-fetch images, CSS, javascript etc files that haven't changed (this reduces the number of HTTP requests) and hence the performance improvement on subsequent page views.

== Installation ==

1. Upload the far-future-expiration.zip file from the Plugins -> Add New page in the WordPress administration panel.
2. Activate the plugin through the "Plugins" menu in the WordPress administration panel.

== Usage ==

To use this plugin do the following:

1) Ensure that the "mod_expires" module is enabled from your host's main configuration file 

2) Check with your hosting provider or if you have access to the httpd.conf file the following line should be uncommented:
LoadModule expires_module modules/mod_expires.so

3) Enable the "Far Future Expiration" checkbox

4) Set the number of days till expiry

5) Select the file types you wish to enable the "far future expiration" feature for by using the checkboxes in the "File Types" section

NOTE: When you use this plugin, the file selected file types are cached in the browser until they expire. Therefore you should not use this on files that change frequently.

== Frequently Asked Questions ==
None
 
== Changelog ==
None

== Upgrade Notice ==
None

== Screenshots ==
Visit the plugin site at http://www.tipsandtricks-hq.com/wordpress-far-future-expiration-plugin-5980 for screenshots and more info.
