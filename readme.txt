=== Random Tweet Widget ===
Contributors: whiletrue
Donate link: http://www.whiletrue.it/
Tags: random tweet, random, tweet, twitter, twitter sidebar, sidebar, social sidebar, widget, twitter widget, twitter feed, simple twitter
Requires at least: 2.9+
Tested up to: 6.3
Stable tag: 1.4.2

Shows a random tweet from a Twitter account in a sidebar widget.

== Description ==
This plugin displays a random post from a Twitter account in a sidebar widget. 

The plugin is based on the Twitter API version 1.1 and requires you
to create a personal Twitter Application on the [dev.twitter.com](https://dev.twitter.com/apps "dev.twitter.com") website.
Within your Application, Twitter provides two strings: the Consumer Key and the Consumer Secret.
You also need two other strings, the Access Token and the Access Token Secret, that you can get
following [this guide](https://dev.twitter.com/docs/auth/tokens-devtwittercom "this guide").
Finally, enter all the Authorization string in the widget options box, along with your favorite display settings: your Twitter Widget is now ready and active!

You can use the same Authorization strings for several widgets and multiple websites. 
Just remember to store them in a safe place!

Your PHP environment needs to have the CURL and OPENSSL extensions enabled.

= Reference =

For more informations: [www.whiletrue.it](http://www.whiletrue.it/random-tweet-widget-for-wordpress/ "www.whiletrue.it")

Do you like this plugin? Give a chance to our other works:

* [Really Simple Share](http://www.whiletrue.it/really-simple-share-wordpress-plugin/ "Really Simple Share")
* [Really Simple Twitter Feed Widget](http://www.whiletrue.it/really-simple-twitter-feed-widget-for-wordpress/ "Really Simple Twitter Feed Widget")
* [Most and Least Read Posts](http://www.whiletrue.it/most-and-least-read-posts-widget-for-wordpress/ "Most and Least Read Posts")
* [Tilted Tag Cloud Widget](http://www.whiletrue.it/tilted-tag-cloud-widget-per-wordpress/ "Tilted Tag Cloud Widget")
* [Reading Time](http://www.whiletrue.it/reading-time-for-wordpress/ "Reading Time")


== Installation ==
Best is to install directly from WordPress. If manual installation is required, please make sure to put all of the plugin files in a folder named `random-twitter-widget` (not two nested folders) in the plugin directory, then activate the plugin through the `Plugins` menu in WordPress.

== Frequently Asked Questions == 

= Does the widget show my tweets in real time? =
Yes they're shown in real time, although you have to refresh the page for them to appear.

= How can I modify the styles? =

You can set your own style modifying or overriding the rule:
div.random_tweet_widget { /* your stuff */ }


== Changelog ==

= 1.4.2 =
* Plugin tested up WordPress 6.1

= 1.2 =
* Changed: switch to the WP HTTP API

= 1.1.6 =
* Added: Twitter API 1.1 support

= 1.0.0 =
Initial release


== Upgrade Notice ==

= 1.0.0 =
Initial release
