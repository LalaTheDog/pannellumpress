Seeing if I can change it to work, somewhat.  The name of the image file, if put in the json or not I have not decided yet.

INSTALLATION

Download the git as a zip, then use the wordpress installer to install it.
Find the plugin under MEDIA->PANORAMAS

Unpack: 
https://github.com/mpetroff/pannellum/releases/download/2.5.6/pannellum-2.5.6.zip
into:
/wordpress/wp-content/plugins/pannellumpress-master/pannellum/src

USAGE

Upload the file with a matching config.json
The name of your photo should be in the json.

Add a shortcode to your post with the name you gave it while uploading.
eg.

[pannellum name='TheWokShop']


OLD README:


UNMAINTAINED!

=== pannellumpress ===
Tags: panorama, pannellum, html5, viewer, image
Requires at least: 3.9.0
Tested up to: 3.9.1
License: LGPLv3
License URI: https://www.gnu.org/licenses/lgpl-3.0.html

A plugin to embed the open source html5 panorama viewer pannellum into Wordpress.

== Description ==
A plugin to embed the open source html5 panorama viewer pannellum into Wordpress. Panorama files as well as their generated config.jspn files can be uploaded to the Wordpress installation and then be displayed with a shortcode.

https://github.com/mpetroff/pannellum
