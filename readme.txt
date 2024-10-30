=== Luftdaten Live Widget ===
Contributors: slowhandasg, bleeptrack
Tags: sensor,environmental data,widget,live
Tested up to: 6.1.1 
Stable tag: 1.4.0
Requires at least: 3.0
Requires PHP: 7.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

== Description ==
Luftdaten Live Widget is a Wordpress Widget which helps to show live data from a sensor node registered at sensor.community.

Choose a Widget title and provide a sensor ID. After saving this information, you can customize the text shown for each sensor value.

You can find the sensor ID at https://devices.sensor.community/sensors. If they are not owned by yourself, you can find them by searching on the map at https://sensor.community/.

Widgets can be used with shortcodes, too! Examples:
[feinstaublive title="Titel" sensorIDs="260,262"]
[feinstaubampel title="Titel" sensorIDs="260"]

An additional shortcode is the map:
[feinstaubkarte sensorIDs="255,260,262" zoom="13"]

Thanks to bleeptrack who wrote this great plugin!

Thank for testing and contributing patches: networx,alexschnapper,abulvenz!

== Changelog ==

= 1.0.1 =
*Bugfix: Error if whitespaces between sensor ids
*Bugfix: Error if sensor offline

= 1.1 =
*new Widget: colorful widget for showing the current PM values. Turns red if over EU threshold.

= 1.2 =
*new Shortcodes: widgets can now be used with shortcodes. See description

= 1.2.1 =
*Bugfix: faulty color on value 10
*optional unit
*optional info text

= 1.3.0 =
*Minor Bugfixs
*Time is now fetchted from Wordpress GTM 
*JSON Requests zu luftdaten api are cached for 120s
*A map is available as shortcode.

= 1.3.1 =
*removed faulty var_dump

= 1.3.2 =
*added support for http and https iframes
*added notification if wrong tick have been copied from the wordpress side for shortcodes

= 1.4.0 =
*patches for php 8.1
*change to new sensor.community urls
*minor cleanups
