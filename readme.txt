=== PMPro Roles ===
Contributors: joshlevinson
Tags: pmpro, membership, wordpress roles, wp residence
Requires at least: 3.0
Tested up to: 4.8.1
Stable tag: 1.1
=========

Makes "WP Residence" theme work with "Paid Memberships Pro" plugin

"Three birds in one shot"
1. Works with Paid Memberships Pro User Roles
2. Add/Update WP Residence User Roles (from 1 to 4)
3. Add/Update Wordpress User Roles (pmpro_role_X)

Fork from https://github.com/strangerstudios/pmpro-roles/ 
Credits and thanks to strangerstudios & joshlevinson

Plugin adds/updates a User Role for WP Residence theme in User profile.

(Additionally it adds a WordPress Role for each Membership that is useful for access control)

Plugin adds/updates a fields value with "X" (like in "pmpro_role_X")
accordingly in the Users profile

Where values in WP Residence are
X = 1 : User
X = 2: Single Agent
X = 3: Agency
X = 4: Developer

e.g. User Role (1, 2 , 3 or 4): 1 = simple user, 2 = agent, 3 = agency, 4 = developer 

Adds a WordPress Role for each Membership Level with Display Name = Membership Level Name and Role Name 
= 'pmpro_role_X' (where X is the WP Residence Membership Level's ID).

== Description ==
This plugin currently requires Paid Memberships Pro and WP Residence theme. 

== Installation ==

1. Upload the `pmpro-roles` directory to the `/wp-content/plugins/` directory of your site.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. That's it. No settings.
 
== Frequently Asked Questions ==

= I found a bug in the plugin. =

Please post it in the issues section of GitHub and we'll fix it as soon as we can. Thanks for helping. https://github.com/eirikvold/pmpro-roles/issues

== Changelog ==
= 1.1 =
* Added a "Delete Roles and Deactivate" link to the plugins page to deactivate with a bit more cleanup. Users are given the "Subscriber" role if they had a membership level based role before.

= 1.0 =
* This is the initial version of the plugin.
