=== Old Core Files ===
Contributors: maor, ramiy
Tags: security, core files, old files, old_files, tool
Requires at least: 3.0
Tested up to: 4.2
Stable tag: 1.2
License: GPLv2 or later

Increase your WordPress security by deleting old core files that exist in the filesystem before hackers exploit them for attacks.

== Description ==

When core is being upgraded, usually some files are no longer used by WordPress, and they are set for removal.

On some occasions, PHP has no permissions to delete these files, and they stay on the server. Old Core Files alerts you to remove old files before hackers attempt to exploit them for attacks.

It's recommended to delete unused themes and plugins as hackers could exploit them for attacks. Same logic applies for deprecated code files.

= Translations =

* Serbian (sr_RS) - by [Borisa Djuraskovic](http://www.webhostinghub.com)
* Hebrew  (he_IL) - by [Rami Yushuvaev](http://GenerateWP.com)

== Installation ==

= Installation =
1. In your WordPress Dashboard go to "Plugins" -> "Add Plugin".
2. Search for "Old Core Files".
3. Install and activate the plugin.
4. Go to "Tools" -> "Old Core Files".

= Updating =
* Use WordPress automatic updates to upgrade to the latest version. Ensure to backup your site just in case.

= Minimum Requirements =
* WordPress version 3.0 or greater.
* PHP version 5.2.4 or greater.
* MySQL version 5.0 or greater.

= Recommended  Requirements =
* The latest WordPress version.
* PHP version 5.4 or greater.
* MySQL version 5.5 or greater.

== Screenshots ==

1. Main plugin screen in Wordpress 3.5
1. Main plugin screen in Wordpress 4.0

== Changelog ==

= 1.2 =

* Bug fix: load translation files.
* Add new screenshot.
* update readme file.

= 1.1.3 =

* Add Hebrew translation by [Rami Yushuvaev](http://GenerateWP.com).
* Improve readme file.

= 1.1.2 =

* Add Serbian translation by [Borisa Djuraskovic](http://www.webhostinghub.com).

= 1.1 =

* Delete buttons removed. We'll have to work on it a bit more before making it available.
* Add screenshot.
* Improve readme file.

= 1.0 =

* Initial release.
