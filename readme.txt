======= Stylish Author Bio: Wordpress Plugin =======
Contributors: bdstar
Tags: author bio,wordpress, plugin, social
Requires at least: 3.5
Tested up to: 4.6
License: GPL-2.0+
License URI: http://www.gnu.org/licenses/gpl-2.0.txt

== Description ==

Display author's biography with social icons in bottom of the posts/pages.

= Contribute =

You can contribute to this source code in our [GitHub](#) page.

= Credits =

* MONO SOCIAL ICONS FONT(http://drinchev.github.io/monosocialiconsfont/).

== Installation ==

> Upload plugin files to your plugins folder, or install using WordPress built-in Add New Plugin installer;
> Activate the plugin;
> You can fill up your biographical info(Profession, Country) and social media links from the deshboard "User" > "Your Profile"
> Go to admin deshboard "Settings" -> "Stylish Author Bio"
> And change the options as your want.
> You can display the Author Bio Section directly into anywhere in your theme using: 

	<?php 
		if ( function_exists( 'get_stylish_author_bio' ) ) {
			echo get_stylish_author_bio();
		}
	?>

== Frequently Asked Questions(FAQ) ==

> What is the compatible wordpress version for this plugin?
  => I have tested it in latest wordpress version 4.6.1. But this plugin is compatible for wordpress 3.5 or higher(recommended) 

> What is the plugin license?
  => This plugin is released under a GPL license.

== Screenshots ==

1. Settings page.
2. New fields in "Your Profile" page.
3. Plugin in action.

== Changelog ==

= 1.0.0 =

* Initial version.

== License ==

Stylish Author Bio is free WordPress Plugin, that's why you can redistribute it and/or modify it under the terms of the GNU General Public License.
