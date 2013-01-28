=== Old Core Files ===
Contributors: maor, ramiy
Tags: security, core files, old files, old_files, tool
Requires at least: 3.0
Tested up to: 3.5
Stable tag: 1.0
License: GPLv2 or later

Increase your WordPress security by deleting old core files that exist in the filesystem before hackers exploit them for attacks.

== Description ==

When core is being upgraded, usually some files are no longer used by WordPress, and they are set for removal.

On some occasions, PHP has no permissions to delete these files, and they stay on the server. Old Core Files alerts you to remove old files before hackers attempt to exploit them for attacks.

It's recommended to delete unused themes and plugins as hackers could exploit them for attacks. Same logic applies for deprecated code files.

== Installation ==

1. Install the plugin
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to Tools > Old Core Files, or just click on the "Settings" link next to the plugin name on the plugins page


== Screenshots ==

1. Main plugin screen, listing old files that may still exist in the filesystem

== Changelog ==

= 1.0 =

* Initial release.