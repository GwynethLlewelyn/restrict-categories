=== Restrict Categories ===
Contributors: mmuro
Tags: admin, administration, cms, categories, category
Requires at least: 3.0
Tested up to: 3.0.1
Stable tag: 1.0

Restrict the categories that users in defined roles can view and edit in the admin panel.

== Description ==

*Restrict Categories* is a plugin that allows you to select which categories users can manage in the Posts edit screen.

== Installation ==

1. Upload `restrict-categories` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to <em>Tools > Restrict Categories</em> to configure which roles and categories will be restricted.

== Frequently Asked Questions ==

= Does this work with custom roles I have created? =

Yes!  Roles created through plugins like Members will be listed on <em>Tools > Restrict Categories</em>

= Will this prevent my regular vistiors from seeing posts? =

No.  This plugin only affects logged in users in the admin panel.

= I messed up and somehow prevented the Administrator account from seeing certain categories! =

Restrict Categories by Role is an opt-in plugin.  By default, every role has access to every category.
If you check a category box in a certain role, such as Administrator, you will <em>restrict</em> that role to viewing only those categories.

To fix this, go to <em>Tools > Restrict Categories</em>, uncheck <em>all</em> boxes under the Administrator account and save your changes.  You can also click the Reset button to reset all changes to the default configuration.

== Screenshots ==

1. A custom role with selected categories to restrict
2. The Posts edit screen with restricted categories

== Changelog ==

**Version 1.0**
* Plugin launch!