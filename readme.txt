﻿=== WP Plugin Reviews ===
Contributors: sudar  
Tags: plugin, review, widget  
Requires at least: 3.5  
Tested up to: 5.5  
Stable tag: 0.4  
Donate Link: http://sudarmuthu.com/if-you-wanna-thank-me  

Displays the latest reviews of a WordPress Plugin in the sidebar.

== Description ==
Displays the latest reviews of a WordPress Plugin in the sidebar.

### Features

#### Sidebar Widget

The Plugin provides a sidebar widget which can be configured to display the latest reviews of a WordPress Plugin in the sidebar. You can have multiple widgets for different WordPress Plugins.

#### Template function

In addition to using the widget, you can also use the following template function to display the reviews of the WordPress Plugin, anywhere in the theme.

`get_plugin_reviews($plugin, $count);`

The following options can be passed in the $options array

- $plugin (string) - WordPress Plugin name. 
- count (int) - defualt 5 -  Number of recent reviews to show

#### Caching

The Plugin caches the reviews that are retrieved for about 12 hours.

#### Styling using CSS

The Plugin adds the following CSS classes. If you want to customize the look of the widget then can change it by adding custom styles to these CSS classes.

- The outer `div` tag has the class `plugin-review`
- The actual review text is enclosed in a `blockquote` tag with class `plugin-review-text`
- The author name is enclosed in a `span` tag with class `plugin-review-author` 

### Development

The development of the Plugin happens over at [github](https://github.com/sudar/wp-plugin-reviews). If you want to contribute to the Plugin, fork the [project at github](https://github.com/sudar/wp-plugin-reviews) and send me a pull request.

If you are not familiar with either git or Github then refer to this [guide to see how fork and send pull request](http://sudarmuthu.com/blog/contributing-to-project-hosted-in-github).

If you are looking for ideas, then you can start with one of the following TODO items :)

### TODO

- Pull Plugin name from custom field
- Shortcode support
- Added an option to display date
- Make the output of widget content plugable

### Support

- If you have found a bug/issue or have a feature request, then post them in [github issues](https://github.com/sudar/wp-plugin-reviews/issues)
- If you have a question about usage or need help to troubleshoot, then post in WordPress forums or leave a comment in [Plugins's home page][1]
- If you like the Plugin, then kindly leave a review/feedback at [WordPress repo page][6].
- If anything else, then contact me in [twitter][2].

### Troubleshooting

If you get timeouts or the error "WP HTTP Error: name lookup timed out" then it means that your server is not timing out before github can respond.

You can use the code from [this gist](https://gist.github.com/sudar/4945588) to increase the timeout.

### Stay updated

I would be posting updates about this Plugin in my [blog][4] and in [Twitter][2]. If you want to be informed when new version of this Plugin is released, then you can either subscribe to this [blog's RSS feed][3] or [follow me in Twitter][2].

Also checkout the [other WordPress Plugins][5] that I have created.

 [1]: http://sudarmuthu.com/wordpress/wp-plugin-reviews
 [2]: http://twitter.com/sudarmuthu
 [3]: http://sudarmuthu.com/feed
 [4]: http://sudarmuthu.com/blog
 [5]: http://sudarmuthu.com/wordpress
 [6]: http://wordpress.org/extend/plugins/wp-plugin-reviews/

== Translation ==

The pot file is available with the Plugin. If you are willing to do translation for the Plugin, use the pot file to create the .po files for your language and let me know. I will add it to the Plugin after giving credit to you.

== Installation ==

Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your WordPress installation and then activate the Plugin from Plugins page. You should see a new widget called "WP Plugin Review" in the widgets pages, which you can drag and drop in the sidebar of your theme.

== Changelog ==

= v0.1 (2013-02-11) - (Dev time: 3 hour) =
*   Initial Release

= v0.2 (2013-02-13) - (Dev time: 0.5 hour) =
* Generated pot file

= v0.3 - (2013-04-24) - (Dev Time: 1 hour) =
* Added documentation

= v0.4 - 2013-04-26 - (Dev Time: 0.5 hour) =
* Fixed some typos and added documentation

== Upgrade Notice ==

= 0.2 =
Generated pot file

== Readme Generator ==

This Readme file was generated using <a href = 'http://sudarmuthu.com/wordpress/wp-readme'>wp-readme</a>, which generates readme files for WordPress Plugins.
