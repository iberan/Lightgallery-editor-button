Light Gallery editor button via Joomla! core Image (com_media) editors-xtd plugin 

Joompolitan Light Gallery content plugin creates galleries from folders under /images directory. Download Light Gallery (http://www.joompolitan.com/lightgallery.html) and install this plugin on your Joomla! 3.6.4 as usual and enable it in Extensions / Plugins / types: content / Light Gallery. Now you can put your galleries into your articles as well, manually entered something like this syntax:

      {lightgallery type=local path=images/path_to_your folder previewWidth=150}Your Gallery Title{/lightgallery}

If you're interesting in editor button, download files from here and copy them following to their directory structure. Enable in Extensions / Plugins / types: editors-xtd / "Button - Image". Open one of your articles in your editor and check the Image button popup window.

Known issue: because of a "dirty hack" some core Joomla! files on, upgrading Joomla! you'll loose this function. You may rebuild it according to comments "by BI" in scripts.
