=== Eazy XMLRPC Pingback Disable ===
Contributors: r0bsc0tt
Tags: XMLRPC, Pingback, Ping, XMLRPC, DDoS, rpc, xml, xml rpc
Requires at least: 4.2
Tested up to: 4.9.1
Stable tag: trunk
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin disables the WordPress XMLRPC pingback ping.

== Description ==
The XMLRPC Pingback Ping can potentially be used as part of a DDOS attack. 
If you do not need the functionality, this plugin will use core functions to disable it. 

== Installation ==
1. Upload plugin to your WordPress Installation
2. Activate plugin

== Frequently Asked Questions ==
= What does this plugin do? =
This plugin disables the XMLRPC Pingback Ping that is built into WordPress. 

== Changelog ==
= 1.0.1 =
* Added pingback.extensions.getPingbacks to remove list, updated tags

= 1.0.0 =
* Initial Release.

== Upgrade Notice ==
= 1.0.1 =
Updated to also remove pingback.extenions.getPingbacks 

= 1.0.0 =
First release.