=== BillyBen Ring ===
Contributors: Billyben
Tags: Links, tag, category, Circle, Ring, SideBar,widget, shortcode, multi instance,simili menu
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=legendreben%40hotmail%2efr&item_name=BillyBen%20Ringt%20WordPress%20Widget&no_shipping=0&no_note=1&tax=0&currency_code=EUR&lc=US&bn=PP%2dDonationsBF&charset=UTF%2d8
Requires at least: 2.8.1
Tested up to: 3.1.3
Stable tag: 2.2.4

Display links, tag, pages, and/or categories by circulars sideBar widgets, full or arrowed circles. Fully customizable. ShortCoded. Mutli Instance.

== Description ==

BB Rings can display your links, with or without their own category, your categories, your page and your posts tags. It show them by circle, full or arrowed, and it is moving!  
It is quite entirely customizable, especially all colors can be indivudually choosen.You can also add the widget to your page or post with shortcode.
Each instance of BB Ring are customizable (see screenshots).
You can choose wether it open a new windows or keep the same for each display's type.
It use an swf integrated by swfObject2 (javascript) in the html page. The Option page also uses Javascript for a really convenient experience.. (...).  

Available in English and French
  
**Requirements**  
  
It require Javascript enabled, and Flash Player 10 or higher.

You can also visit <a href="http://82.228.191.29/asblog/?page_id=488&lang=en">Widget Page</a>  
  
*note : ColorPicker javascript code were from* <a href=\"http://odvarko.cz/\">Jan Odvarko</a> (<a href=\"http://jscolor.com/\">jscolor</a>) 

*WPML Compatibility : It can display colors for different languages, based on the admin language choosen colors.*

== Installation ==

1. Upload the "BillyBenRing.zip" file. 
2. Unzip the content
3. Copy the "BillyBenRing" folder (found in "billyben-rings" folder from unzipping) to your wordpress pluging folder
4. Activate the plugin through the "Plugins" menu in WordPress  
5. Configure the Ring's colors on "BB Ring Colors option " page (by the BillyBen Ring option menu)  
6. Configure each widget by the BillyBen Ring option menu, create and delete. 
7. At the widget page, add BillyBenRing to your sidebar, choose witch Widget Id it refers (sometimes the ifd of the widget 0 doesn't appeat in choices, just create another one)

Note : For some configurations (don't know which) the auto install by the admin panel failed (you will see the error "invalid header"), prefer an ftp installation.

== Frequently Asked Questions ==

= When I switch Language with WPML I lost data =
Make sure you have defined each traduction for each item, and you have links those traduction

= No "0" id appear in choices for widget choice in sidebar widget panel =
Yes, i know, sometimes for some unknow reason it does'nt. just create an another one in the bbr widget configuration page.


Please Ask! <a href="http://82.228.191.29/asblog/?page_id=488&lang=en">Widget Page</a>


== Screenshots ==

1. The BillyBen Ring widget displaying different configurations.
2. The BillyBen Ring Menu (probably at the bottom)
3. The BBR's Options Page - Widget Option creation
4. The BBR's Color Option page (with a drag!)
5. The BBR Help Page head
6. The SideBar configuration of BBR Widget

== Changelog ==
= 2.2.4 = 
* Fix some url bug (i.e "Create New" widget option)
* update some deprecated function
* add some missing french traduction
note : thanks to <a href="http://www.le-savoir-est-une-arme.info/" target="_blank">Lillia<a> for feedbacks and test
= 2.2.3 =
* Fix a bug about the "create Gradient" button with WPML multilingual configuration
= 2.2.2 =
* Add French traduction
* fix an FF bug
* fix a wpml compatibility issue
= 2.2.1 =
* add rings position (top, left, bottom, top left, etc...)
* add preview for Widget Option page
* add possibility to not display choosen item (checkbox at the left of color)
* add possibility to re organise item (simply drag n drop)
* Rings now crop text if too long
* Rings now follow mouse when over
= 2.1.1 =
* minor bug fixed
= 2.1.0 =
* Add ShortCode
* Change Menu - add specific BBR Menu

Updating from version 2.0 should not erase your configuration
= 2.0.0 =
* It is now Multi instance
* added the choice for _self or _blank for each category

**Important** Upgrading to this version will initialize Instance Setting but your defined colors for each category will remain the same.

= 1.0.1 =  
* Add Page to the display possibility
* Turn Option page to internationalization (so can be translate)

= 1.0 =  
* Adding some modification to be partially compatible with wpml plugin

== Options description == 

= ShortCode =
just add [BBR id='X'] to your post/page. You can choose Widget alignement by [BBR id='X' align='left'], align could be 'left', 'right' and 'middle', default is middle.
For advanced shortcode use, please refer to the Help Page of BBR.  

= Instance Options = 
  
**Dimensions** 
  
   * Width, Height : The width and Heigth of the swf  
   * Ring Size : the thickness of each ring  
   * First Ring Size : the first ring inner radius 
   * Position of rings : position ofthe center (middle, top, left, bottom left,....) 
  
**Rings**  
  
   * Text Color (Off/Over) : the two text colors, when mouse is up or out  
   * Ring Glow Color : the glow color applied when mouse is over  
   * Space between rings : the spacing between rings  
   * Ring fit text : rings are full filled ("Entire") or arrowed ("fit")  
   * Start Alignement : The alignement of rings- for "Decal" chose the angle step between rings (can be negative)  
   * Start Angle : the start angle for the rings alignement  
   * Text Direction : The direction of the text turn to the center ("in") or off the center ("out") or it can follow the ring’s perimeter (the two other)  
  
**What to show**  
  
Here you chose what you want to display : Links, Categories, pages and/or Post Tag.
For "links" you can choose wether you want to show their categories (display link cat). 

= Color Options =

Click on tab buttons to show the corresponding table, it does not influence instances display.
At the top of each table their is a dropDown list which allow you to choose where the link will open.
  
**Color Chooser**  
  
You can Choose any color you want for each rings. Simply click into the text field and it will display a colorPicker. At the top of each category you can find a "Create Gradient" button, which allow you to create a color gradient for its category.


== Known Issue == 

* Whith Firefox 4 (at least), when you click to a "_self" link and then get back, it disable clik onto the widget instance that call it... don't know why for the moment.
