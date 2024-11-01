=== ShootQ Integration ===
Contributors: skooks
Donate link: http://www.flauntbooks.com/shootQ/
Tags: shootq, shootq integration, shootq form, prophoto, pro photo, flaunt books
Requires at least: 2.5.0
Tested up to: 3.3.1
Stable tag: 2.0

Integrates your shootQ account with your blog.  Display your public contact form and/or process your ProPhoto Blog 2, 3 & 4 contact form into shootQ.

== Description ==

Integrates your shootQ account with your blog.  You can integrate your public contact form into any page or post.  You can also integrate your ProPhoto Blog 2, 3 & 4 contact form with shootQ. You can also use Contact Form 7, CformsII and custom forms to send data directly to shootQ.  This plugin is provided free by Flaunt Books.

== Installation ==

**Step One:**
Download the attached plugin.  

1. Upload the `shootq-integration` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

**Step Two:**
Login to your Wordpress Blog
  -  Click on Plugins > Add New > Upload
  -  Browse and find attached .zip file
  -  Click Upload
  -  Activate The Plugin

**Step Three:**
In your Wordpress admin under the Settings option click on ShootQ.

Login to ShootQ -> Click Settings -> Click Integrations on the left column >
  -  Enable Public API Access if necessary.
  -  Copy / Paste API Key & Brand Abbreviation into the fields on the ShootQ settings page.

**Step Four:**
Create or edit a page / post and insert the following shortcode:
> [shootq]

You can add the form to your theme using this in your theme:
'<?php code(); // goes in backticks ?>'


**Step Five:**
Submit a form submission test. 

You can then style your contact form further inside of the shooQ Public Area. 
To access the public area click on Settings -> Click on Public Area on the left column ->
Style setting and options are available for further customization.

**Pro Photo 2 & 3 Integrated!**
This Free version includes the function hook so your Pro Photo contact forms send their data directly into ShootQ.  Just activate it and it's ready to go. Is that cool or what!

Notice: You'll need to be using ProPhoto 3 with a build number of #664 or higher for the plugin to work instantly without the need to modify any theme files.  
If you aren't, contact ProPhoto here: http://www.prophotoblogs.com/support/contact/ for an update.



== Frequently Asked Questions ==

= How easy is this to install? =

It can be installed, activated & integrated within 2 minutes.

= After activating, how do I display my contact form? =

Create or edit a page / post and insert the following shortcode:
> [shootq]

You can add the form to your theme using this in your theme:
'<?php code(); // goes in backticks ?>' 

= Can it process my ProPhoto Contact Form? =
You'll need to be using ProPhoto 3 with a build number of #664 or higher for the plugin to work instantly without the need to modify any theme files.  
If you aren't, contact ProPhoto here: http://www.prophotoblogs.com/support/contact/ for an update.


= The plugin is being unzipped when I download it and I'm using a Mac.  How do I fix that? =

If you are using a Mac please be sure that your browser does not unzip or decompress the attachment.  It needs to remain intact as shootq.zip. There are settings for both Safari & Firefox which allow you control over whether downloads and attachments are automatically unzipped / decompressed. If you can't solve this you'll need to upload (FTP) the unzipped shootq folder into your wordpress plugins directory.  The folder name should be "shootq" and it should contain 3 php files and 2 folders.
You can then visit your plugins page in Wordpress and activate the Plugin.  Skip to Step Three.

== Screenshots ==

1. Coming soon...


== Changelog ==

= 2.0 =
* Fixed hooks to enable proper integration with updates to both shootQ and ProPhoto.
* Reverse compatibility fixes for all version of ProPhoto Blogs

= 1.6 = 
* Added expanded ability for any form to initiate shootQ by adding a hidden field name shootq.
* Fixed several other styling and data saving issues.
* Added better links to the settings from the plugin description and activation links.

= 1.5 = 
* Fixed a save settings problem.

= 1.4 = 
* Updated ProPhoto instructions as you need to be using ProPhoto 3 with a build number of #664 or higher. Contact ProPhoto http://www.prophotoblogs.com/support/contact/ for an update. 

= 1.3 =
* Added ProPhoto blog form hook so ProPhoto users don't have to modify their templates.
* Improved the styling of the plugin by utilizing the JQuery UI Library.  Added Tabs & Accordian for specific instructions and FAQ.
* Added Tweet this and a link to contact Flaunt Books for help with integration & customization.

= 1.2 =
* Fixed minor tweaks to admin & plugin page.

= 1.1.2 =
* Fixed image & style sheet errors for admin of plugin.

= 1.1.1 =
* First stable release

= 0.1 =
* Initial Setup & Beta Testing

== Upgrade Notice ==

= 2.0 = 
Fixed compatibility issues with current and previous versions of ProPhoto.  Also updated to latest shootQ API changes.

= 1.6 = 
Use any form you like by adding the shootq hidden field to it.  Improved debugging and a few minor issues solved.

= 1.5 = 
Fixed a save setting problem.  It is important to udpate as you will not be able to save your API Key / Brand Abbreviation.

= 1.4 =
You must be running ProPhoto 3 with a build number of #664 or higher for the plugin to work instantly. Instructions updated.

= 1.3 =
Addition of ProPhoto hook so the editing of P2 & P3 Theme files is not required. Yay!

= 1.2 =
Fixes to plugin download & information page.

= 1.1.2 =
Styling fixes for plugin settings.

= 1.1.1 =
This version is the first stable release.