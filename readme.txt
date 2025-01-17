=== Plugin Name ===
Contributors: bjoerne
Donate link: https://www.bjoerne.com/navigation-du-lapin-blanc/donate/
Tags: navigation, menu, cms, content management system, sitemap, page, category, url, main navigation, sub navigation, metadata, item, web design
Requires at least: 2.8.0
Tested up to: 4.8.2
Stable tag: trunk

This plugin provides integrated navigation for your website. Use WordPress as a CMS for your website and think in navigation terms (main, sub etc.)

== Description ==

This plugin provides integrated navigation for your website. Thus you can use WordPress as a CMS for your website and think in terms of main navigation, sub navigation etc. A navigation item can link to page, a category, directly to the first sub navigation item (if no own content exist for this item), an external url or a sitemap page. There are a lot of helpful methods to realize a website navigation with little effort like printing the navigation on any level (main, sub, sub sub etc.), searching single navigation items and handle them individually, using cross links in the content, providing a sitemap page and so on.

Plugin page with a large documentation and a lot of examples: [http://www.bjoerne.com/navigation-du-lapin-blanc/](http://www.bjoerne.com/navigation-du-lapin-blanc/)

== Installation ==

1. Upload the all plugin files to the `/wp-content/plugins/` directory or a special directory e.g. `/wp-content/plugins/navigation-du-lapin-blanc` 
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Edit your templates to use the navigation provided by the plugin.

== Frequently Asked Questions ==

= How can I integrate a category into my navigation? =

Please have a look at the tutorial section of the plugin site.

= How can I link to an external url? =

Please have a look at the tutorial section of the plugin site.

= How can I use metadata? =

Please have a look at the tutorial section of the plugin site.

= How can I integrate a sitemap? =

Please have a look at the tutorial section of the plugin site.

= How can I avoid a page being displayed as a menu item automatically? =

Please have a look at the tutorial section of the plugin site.

= How can I link pages from my page content? =

Please have a look at the tutorial section of the plugin site.

== Screenshots ==

You can find a lot of screenshots on the plugin page. There are a lot of examples with screenshots.

== Changelog ==

= 1.0.0 =
* Use a navigation on every level you want (main, sub, sub sub navigation etc.)
* Use metadata for your pages (e.g. define which graphic should be used in the head section)
* Hide pages if they must not appear in the navigation
* Integrate categories, the visitor won't see differences between kinds of elements (page, category etc.)
* Link navigation items to the first sub navigation item. For example let "About us" have no content and link to the page "Our team" which is the first child page
* Link to external urls
* Integrate a sitemap
* Use cross links in your content
* Set individual attribute at your navigation items (e.g. tooltip or css)

= 1.0.1 =
* Bugfix: Now other permalink pattern are supported

= 1.0.2 =
* Pages of the type 'delegate_to_first_child' aren't considered by the seach anymore

= 1.0.3 =
* Now single posts are supported. If you integrate a category into your navigation tree (with this plugin) and then invokes a single post the plugin shows the category as selected in the navigation.

= 1.0.4 =
More supported attributes for menu items (onmouseover, onmouseout, onclick)

= 1.0.5 =
* Build link to category with WordPress API instead of concatenating the string

= 1.0.6 =
* Support categery name and category slug to be used as value for bjoerne_category_name when integration categories in the navigation
* Remove phpDoc from plugin code

= 1.1.0 =
* Compatibility with PHP 7.0

= 1.1.1 =
* Fix deprecated PHP code according to PHP warnings.
