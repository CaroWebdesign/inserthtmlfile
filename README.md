# Insert HTML File

This is a little plugin I developed for work and thought the general community may wish to use it. 
Clicking on the icon opens a dialog box, where the user can select a file containing text or HTML. The content is then inserted into the current document. We use it for standard sections of text or pre-built tables that we wish to include, on multiple pages.

# Installation
Extract the contents of the zip file into your plugins directory
Now add the plugin in your config.js or custom js configuration file:

    e.g. config.extraPlugins='inserthtmlfile';  or config.extraPlugins='someotherplugin, inserthtmlfile'; 
    
In your toolbar configuration, add a new 'inserthtmlfile' item in the place where you want the button to show up.

# Drupal Installation

As above but instead of editing your tool bar configuration on the last line: 

goto /admin/config/content/ckeditor
edit the Profile where you wish to add the button.
expand the Editor Appearance section
Drag the icon from "Available buttons" to the "Current toolbar"
Save

# Demo

See the video at https://youtu.be/7dCa5jBXmz0
