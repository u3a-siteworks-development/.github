# u3a SiteWorks Organization README

Welcome.

This organization belongs to the national [University of the Third Age (u3a)](https://www.u3a.org.uk/).

## About the u3a

The u3a is a UK-wide movement of 1000+ charities that create the opportunity for members to come together 
to share skills and learn for fun. The u3a is composed of a collection of groups (u3as) that run local and 
online member-led learning across the UK, in particular for those no longer in full time work. Each u3a has its own web site, and many of these websites now the use the u3a-Siteworks softarew and hosting service.

## About u3a SiteWorks

The [Siteworks project](https://siteworks.u3a.org.uk/) is a development group whose purpose is to define and 
develop common functionality shared by many u3a websites to provide a framework for a common look and feel without compromising on flexibility of content. 

This framework is composed of a custom WordPress theme which delivers the common style and a cluster of WordPress plugins which supply  
customisable basic features such group lists, event lists, venues and contact pages. 

These plugins and theme are all in the repositories associated with this organization and are dependent on minimal WordPress configuration and the metabox plugin.

Siteworks has a [developer forum](https://u3awpdev.org.uk/) including more detailed [instructions](https://u3awpdev.org.uk/viewtopic.php?t=193) than those in the following paragraphs.

## Devlopment of the software
The plugins and theme are open source and licensed under [GPL](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html) for public use.
Development of the software is carried out by members of this u3a-siteworks-development GitHub Organisation. Everyone in the team has at least write access and some have administration access. If a member of the team feels they need more access rights, then they may request any administrator to change them.
All development team guidance and procedures are held in [the documentation repository](https://github.com/u3a-siteworks-development/u3a-siteworks-documentation).

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
  * Download the three main zip files [u3a-siteworks-core](http://siteworks.u3a.org.uk/wp-update-server/packages/u3a-siteworks-core.zip), [u3a-siteworks-configuration](http://siteworks.u3a.org.uk/wp-update-server/packages/u3a-siteworks-configuration.zip) and [u3a-siteworks-contact_form](http://siteworks.u3a.org.uk/wp-update-server/packages/u3a-siteworks-contact-form.zip).
  * Download the theme [u3a-siteworks-theme](http://siteworks.u3a.org.uk/wp-update-server/packages/u3a-siteworks-theme.zip). 
* Or: 
  * Check out the plugin repositories associated with this organization - each repository base directory can be copied into the plugins directory and activated. The main branch contains the latest development version, and the highest numbered release branch contains the current stable version.

* In the WordPress admin dashboard install and activate the three u3a plugins and the theme.

* Optionally install these additional plugins that are included with the 'Local' demo system:
	* [u3a SiteWorks Maintenance Mode](http://siteworks.u3a.org.uk/wp-update-server/packages/u3a-siteworks-mm.zip) - Provides a maintenance mode in which the site is unavailable to visitors but editable by administrators.
    * [u3a SiteWorks Dashboard](http://siteworks.u3a.org.uk/wp-update-server/packages/u3a-siteworks-dashboard.zip) - Adds a SiteWorks information panel to the WordPress dashboard.
    * [u3a SiteWorks Import Export](http://siteworks.u3a.org.uk/wp-update-server/packages/u3a-importexport.zip) - Facilitates the export and import of groups, venues, contacts and events from a SiteWorks site to CSV.
    * Gallery and Image Block Lightbox - https://en-gb.wordpress.org/plugins/gallery-block-lightbox/
    * IMSanity - https://en-gb.wordpress.org/plugins/imsanity/
    * Meta Field Block - https://en-gb.wordpress.org/plugins/display-a-meta-field-as-block/
    * Gutenslider - https://wordpress.org/plugins/gutenslider/
