=== WH Tweaks ===
Contributors: webheadllc
Donate link: https://webheadcoder.com/donate-wh-tweaks
Tags: ideas, bugs, problems, codex, trac, fix, security, login, hide version, shortcode, current date, password change, tweaks, add user, harden, optimize, html excerpts, excerpt links, wp_mail, return-path, workaround, multisite, sidebar
Requires at least: 3.5
Tested up to: 4.7.4
Stable tag: 0.73
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Common functionality WordPress core should have but maybe shouldn't

== Description ==

Often times, ideas from WordPress Ideas (https://wordpress.org/ideas/) or bugs from WordPress Trac (https://core.trac.wordpress.org/) take years to make it into WordPress Core.  Sometimes even if everyone agrees on the fix it still doesn't get in.  This plugin is the temporary patch you've been waiting for.  Activate any feature you want and disable any you don't want.  Additional features will be occasionally added as I find them missing.

* Allow excerpts to show links.
* Obscure login errors so an attacker will not know if a username exists.
* Hide WordPress version in both meta tags and script inclusions.
* Make category children highlighted with a subtle gray background.
* Some added shortcodes.
* Customize login.
* Remove emoji scripts and styles.
* Automatically set the Return-Path to the From address if it's not already set (Trac #22837).
* Show private pages in parent dropdowns (Trac #8592).
* Allow commas in category terms (Trac #14691).
* Show sidebar from main site in Multisite (Trac #22370).
* Disable default WordPress REST API endpoints.
* Remove author pages from public viewing.
* Redirect user enumeration to 403 Forbidden page.

Each of these options can be turned on or off on the Settings -> WH Tweaks page.   

== Changelog ==

= 0.73 =  
Fixed reset password error on some woocommerce installations.  

= 0.72 =  
Removed adding sender email to "replyto".  as this is not needed.  

= 0.71 =  
Added option to redirect user enumeration to 403 Forbidden page.  
Removed From email option.  let other plugins handle this.  

= 0.7 =  
Added option to remove author pages from public viewing.
Added option to adjust From name in the WordPress emails.  

= 0.6 =  
Added option to disable the default REST API endpoints.  

= 0.5 =  
Added option to show a static version of the main site's sidebars on Multisite.  

= 0.4 =  
Added option to show private pages in parent dropdowns.  
Added option to allow commas in category terms.  
removed useless overwrite filter.  

= 0.32 =  
Fix php warning when obscuring wp version.  

= 0.31 =  
Prefix hex2rgb function.

= 0.3 =  
Add option to automatically set the Return-Path when sending with wp_mail.  

= 0.2 =  
Allow excerpts to show links.

= 0.1 =
Initial release.

