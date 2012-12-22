=== BookMaster ===
Contributors: Doc4
Donate link: http://www.doc4design.com/donate
Tags: blogroll, blogroll titles, blogroll categories, blogroll category, blogroll category names, links, link titles, link categories, link category, link category names, bookmarks, bookmark titles, bookmark categories, bookmark category names
Requires at least: 2.7
Tested up to: 3.5
Stable tag: 1.0


== Description ==

= Plugin URL =
http://www.doc4design.com/plugins/bookmaster/

BookMaster is our answer to what we feel is an odd issue with the WordPress wp_list_bookmarks tag. For those that have exercised the use of wp_list_bookmarks, you are well aware that it is not possible to use the bookmark category title alone without calling on the bookmarks themselves. This is, of course, with the exception of excluding all bookmark categories and this can be painful if there are a lot of them.

With the introduction of BookMaster, we have resolved this small issue. The plugin allows you to place a bookmark category title anywhere you want without showing the bookmark links. This presents the administrator with the option of changing the bookmarks title using the bookmarks menu which will auto change the bookmark title within the code. Using this plugin will prevent the unnecessary need to alter template files.

In the example below we are displaying only the title of bookmark category 3 within an h1 style tag. We can now alter this information from the bookmarks admin panel simply by changing the bookmark category name. Displaying directly below the title the bookmarks from Category 7 will print in an unordered list.

While not the most effective use of this plugin the example utilized below is for educational purposes.


== Screenshots ==

View Screenshots:
http://www.doc4design.com/plugins/bookmaster
 

== Installation ==

To install the plugin just follow these simple steps:

1. Download the plugin and expand it.
2. Copy the bookmaster folder into your plugins folder ( wp-content/plugins ).
3. Log-in to the WordPress administration panel and visit the Plugins page.
4. Locate the BookMaster plugin and click on the activate link.
5. Insert wp_list_bookmaster('category=3'); wherever you would like to show a bookmark category title. Be sure to change the category number to the category you would like to display.