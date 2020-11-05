Ultimate .htaccess paraniod-wordpressbloggers
======================================

All in one for paranoid wordpress owners,  .htaccess1,

upload it your root folder. Security on wordpress for paranoid bloggers. 

I want my wordpress fast and secure by: .htaccess. 
Please help me make it better! Write a comment, if you miss something.   //The blogging lady

* Updated: 20-11-05  Updated och new!
* Updated: 2020-08-17  Delated lots of stuff - not a threat nowdays in, WP: 5.5+
* Updated: 2020-02-03 Added security and delated one not neeeded!
* Updated 2019-10-15 Added security and delated one!
* Uppdated 2019-04-10  / Some new threats!
* Updated: 2019-10-13  / Added security risk!
* Updated: 2018-07-14  / Some doubles taken away:)
* Updated: 2018-08-17  / With the latest! :)
* Updated: 2018-08-21  / with a new .htacces = More speed! + a new threat I added:)
* Updated: 2018-08-28  /with 1 one new thread I found:)

Extra security; wp-config.php  sset the file rigts to: 444.
Insert AFTER: require_once(ABSPATH . 'wp-settings.php');


define('DISALLOW_FILE_EDIT',true);
define('DISALLOW_FILE_MODS',true);
define('WP_DISABLE_FATAL_ERROR_HANDLER',true);

Set: robots.txt: 444
Other files like, google, bing to: 444  //not write but readable!
