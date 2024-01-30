# u3a SiteWorks Organization README

Welcome.

This organization belongs to the national [University of the Third Age (u3a)](https://www.u3a.org.uk/).

## About the u3a

The u3a is a UK-wide movement of 1000+ charities that create the opportunity for members to come together 
to share skills and learn for fun. The u3a is composed of a collection of groups (u3as) that run local and 
online member-led learning across the UK, in particular for those no longer in full time work. Each u3a has its own web site, and these
are currently migrating towards SiteWorks from the older [SiteBuilder system](https://u3asites.org.uk/code/index.php) 

## About u3a SiteWorks

The [Siteworks project](https://siteworks.u3a.org.uk/) is a development group whose purpose is to define and 
develop common functionality shared by all u3a websites to provide a framework for a common look and feel without compromising on flexibility of content. 

This framework is composed of a custom WordPress theme which delivers the common style and a cluster of WordPress plugins which supply  
customisable basic features such group lists, event lists, venues and contact pages. 

These plugins and theme are all in the repositories associated with this organization and are dependent on minimal WordPress configuration and the metabox plugin.

Siteworks has a [developer forum](https://u3awpdev.org.uk/) including more detailed [instructions](https://u3awpdev.org.uk/viewtopic.php?t=193) than those in the following paragraphs.

The plugins and theme are open source and licensed under [GPL](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html) for public use.

## Trying Siteworks for yourself

You can try the plugins locally by running our demo site in a pro-configured local-WP, or you can install the plugins individually on a fresh
WordPress installation

### Installation steps using Local WP - Recommended

If you have Local WP installed you can download the file [siteworksdemo.zip](https://u3a-llandrindod.org.uk/training/siteworksdemo.zip) and import 
this into Local (File -> Import site). This will give you a WordPress installation set up as below PLUS some sample content.
 
After importing the site, switch on 'One-click admin' and you will be able to access the admin pages using the 'WP Admin' button.

### Manual installation steps for WordPress administrators.

* Set up a fresh installation of WordPress using your preferred development environment
* Make sure mod_rewrite (or equivalent) is available on your server and set the WordPress Settings -> Permalinks stucture to use "Post name"
* Install and activate the Meta Box plugin by metabox.io. It is essential that this is activated before activating the SiteWorks core plugin.

* Either:
  * Download the three main zip files (u3a-siteworks-core, u3a-siteworks-configuration and u3a-siteworks-contact_form) from <TBD>.
  * Download the theme (u3a-siteworks-theme) from the same location. 
* Or: 
  * Check out the plugin repositories associated with this organization - each repository base directory can be copied into the plugins directory and activated. The main branch contains the latest development version, and the highest numbered release branch contains the current stable version.

* In the WordPress admin dashboard install and activate the three u3a plugins and the theme.

* Optionally install these additional plugins that are included with the 'Local' demo system:
	* u3a SiteWorks Maintenance Mode - Provides a maintenance mode in with the site is unavailable to visitors but editable by administrators.
        * u3a SiteWorks Dashboard - Adds  siteworks information panel to the WordPress dashboard.
        * u3a SiteWorks Import Export - Facilittes the export and import of groups, venues, contacts and events from a siteworks site to CSV.
        * Gallery and Image Block Lightbox - https://en-gb.wordpress.org/plugins/gallery-block-lightbox/
        * IMSanity - https://en-gb.wordpress.org/plugins/imsanity/
        * Meta Field Block - https://en-gb.wordpress.org/plugins/display-a-meta-field-as-block/
        * Gutenslider - https://wordpress.org/plugins/gutenslider/
