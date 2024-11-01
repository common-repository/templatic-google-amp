=== Templatic-Google-AMP ===
Contributors: rbhavesh
Tags: AMP, google AMP,Accelerated Mobile Pages, templatic
Requires at least: 3.5
Tested up to: 5.0
License: GPLv2 or later

== Description ==

To work with [Templatic](http://templatic.com/) AMP plugin just type 'amp' keyword after any archive, category, details or any page URL it will display AMP version of that page.

After activating this plugin go to Plugin’s settings >> and make sure that “AMP” option is enabled at your site to use this plugin.

You can see different options here, like AMP theme, Header code and Footer code.

AMP Theme : By default, it will use 'templatic' template which is available on " plugins/Templatic-AMP/templates " this folder.

Once this plugin is activated at your site your site will dynamically generate AMP version. If you want to check the AMP version you need to append " /amp " after your page URL. if your page URL is " www.yourdomainname.com/page1/ " then you need to add the "/amp" after this URL as shown here. " www.yourdomainname.com/page1/amp/ ". It will load the pages instantly with mobile optimised content at your site.

You can change style add your style into " \plugins\Templatic-Google-AMP\templates\templatic\style.php " this file, if you want additional styling.

One of our customers asked “ whether this theme supports Google AMP? ” in a pre-sales question. Which makes us curious and digging into it, it looks like Google AMP is targeted towards mostly the content-only, news and article content so that the user can read the news or article faster and not for the content and images rich, dynamic pages.

AMP means Accelerated Mobile Pages, in other words, it strips down all the design and functionality to show content only page to the user as soon as possible. Certainly, this means it is not built for advanced WordPress sites with heavy content.

However, what if you want to use Google AMP on a regular WordPress blog? We looked at the possible options and there exists an official WordPress plugin that lets enables google AMP on your site but only for blog posts. It wouldn't work for different post types & taxonomies, pages or category archives.

We believe WordPress pages and WordPress posts under Taxonomies should be able to use the power of Google AMP.


Any WordPress blog once gets past few hundred blog posts might need to separate content into different taxonomies to keep things organised. For example, if you are running a Medical portal with hundreds of posts, you might have different taxonomies such as diseases, nutrition etc. so you can better manage your WordPress blog.

Also, a content heavy WordPress blog might have 15-20 important pages, mostly content but they are not a WordPress posts.

So we upgraded the plugin to support WordPress Pages and taxonomies.

We are happy to release an upgraded, Free WordPress plugin today that takes Google AMP further by supporting the missing pieces – WordPress Pages, Taxonomies and category archives.

How to use this Templatic Google AMP WordPress plugin?

1. Download this Templatic Google AMP Plugin from above link.
2. Connect to your WordPress dashboard (wp-admin) and navigate to Plugins >> Add New Plugin >> Upload Plugin >> Now upload the downloaded (Templatic-Google-AMP.zip) file >> Click on “ Install Now ”
3. Once you install this plugin successfully, click on “ Activate Plugin ”.
4. After activating this plugin go to Plugin’s settings >> and make sure that “ AMP ” option is enabled at your site to use this plugin.
5. You can see different options here, like AMP theme, Header code and Footer code.
6. AMP theme: This option is used to change the template. If you want to change the default template “ templatic ” then please go to this mentioned file location and place your template here.
File location: “ plugins\Templatic-Google-AMP\templates\ ” 
Note: You need to place two files “header.php” and “ footer.php ” to your template files from the default template “ templatic ”
7. Header Code: if you want to use the Google Analytics for a header then you can place your code in this area.
8. Footer Code: if you want to use the Google Analytics for footer then you can place your code in this area.
Once this plugin is activated at your site your site will dynamically generate AMP version. If you want to check the AMP version you need to append “ /amp ” after your page URL. if your page URL is “ www.yourdomainname.com/page1/ ” then you need to add the “ /amp ” after this URL as shown here. “ www.yourdomainname.com/page1/amp/ ”. It will load the pages instantly with mobile optimised content at your site.

== Installation ==

**Installation**

1. Upload the entire 'Templatic-Google-AMP' folder to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= How do I create a custom template? =

Yes, you can.Copy plugins/Templatic-AMP/templates/templatic folder and rename it to your desired template name and put that same name into AMP setting page on the back end side.

= Can I include this plugin in my theme for distribution? =

Yes. Source credits for the plugin should remain intact, per GPL requirements.


== Screenshots ==
1. This is how you can set the backend settings for AMP
2. This is how will see the detail page with amp

== Changelog ==

= 0.0.1 =
* Initial Release