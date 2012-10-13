=== Photoswipe for NextGEN Gallery ===
Contributors: gsenas
Tags: Photoswipe, NGGallery, mobile, ipad, iphone, android, slideshow, media gallery, NextGEN gallery
Requires at least: 3.0
Tested up to: 3.4.1
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Automatically use Photoswipe to navigate NextGEN galleries when using a mobile browser

== Description ==

The default NextGEN gallery navigations (Shutter, Thickbox, etc...) fall short when using a mobile browser?
Now you can use Photoswipe, the best mobile image browser, just installing this plugin. The default gallery effect and configuration is kept when accessing from a desktop browser.

After activation you'll find a new Photoswipe submenu in the NextGEN Gallery menu, allowing you to configure how the plugin works.

Please note, I am not the developer, or related in any way with of the authors of [Photoswipe](http://www.photoswipe.com/ "Photoswipe webpage") or [NextGEN Gallery](http://wordpress.org/extend/plugins/nextgen-gallery/). This plugin is only intended to make Photoswipe integration with NextGEN Gallery dead simple.

= Options =

The plugin is ready to be used with zero configuration, but to make testing easier, there are 3 configuration options:

* *Replace viewer with Photoswipe only on mobile browsers*

This is the default behavior, and will replace the NextGEN Gallery Effect with Photoswipe only when a mobile browser is detected. 

* *Always replace viewer with Photoswipe*

Useful for testing.

* *Never replace the viewer*

Disables the plugin. Much like deactivating the plugin.

== Installation ==
STEP 0: Make sure you have the [NextGEN Gallery](http://wordpress.org/extend/plugins/nextgen-gallery/) plugin already installed and activated!

*Automatic Installation*

1. Download and install Photoswipe for NextGEN Gallery using the built in WordPress plugin installer.


*Manual Installation*

1. Download the zip file and unzip it.

2. Upload the ngg-photoswipe folder to your `/wp-content/plugins/` directory. Alternatively, use the Wordpress plugin install in `Plugins >> Add New >> Upload` to upload and install the zip file.

3. Activate the plugin through the `Plugins` menu in WordPress.

Done! Photoswipe will be used when accessing from a mobile browser. 

If you want to be sure, check your "Gallery" menu. A new Photoswipe section should be there.

== Frequently Asked Questions ==

= How is the standard effect (Shutter, Thickbox...) prevented when using Photoswipe? =

The javascript added when a mobile browser is detected does two things:

a) Fire the Photoswipe viewer when you click on a image

b) Remove the default additional HTML markup added in the "Link Code Line" of the Effects tab in NextGen Gallery Options

That way, the standard defined effect won't fire when Photoswipe is used. Please don't change the markup, or two viewers may fire at the same time.

If you absolutely need to change the "Link Code Line", change the ngg-photoswipe.js to remove the specific markup you add.
 
= Will the image descriptions show? =

Yes, the description will show behind the title, if the image has one.

= Is there any menu page to change the default Photoswipe options? =

No, sorry. But you can edit the ngg-photoswipe.js file to achieve what you want.

== Screenshots ==

1. Plugin options - Choose when Photoswipe should be applied.
2. New Gallery submenu
3. Result 

== Changelog ==

= 1.0 =

* Hello world! Initial version.

== Upgrade Notice ==

Thanks for using this initial version.

