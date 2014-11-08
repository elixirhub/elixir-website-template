================
IMPORTANT NOTES
================

The website needs to run on a server, connected to the internet in order to work properly,
see "Viewing the website" below.

This ELIXIR website is built on top of HTML5 Boilerplate and additionally uses CSS from 
960 Grid System to implement the 24 column grid structure. 

css/main.css has been modified to include all the relevant css files. The boilerplate css
that was ORIGINALLY in main.css has been moved into _boilerplate-default.css. To maintain 
the integrity of the structure and code, the only css files that you should edit are:

_base.css to add your base styles

_layout.css for page layouts

_features.css for individual page features

All of these css files can include css that overrides css from 960 Grid and the Boilerplate

Have a look at main.css to see the order in which the css files are included.

==================
DOCUMENTS / HELP
==================

HTML5 Boilerplate documentation: https://github.com/h5bp/html5-boilerplate/blob/v4.3.0/doc/TOC.md

HTML5 Boilerplate: http://html5boilerplate.com

960 Grid System: http://960.gs

960 Grid System Slides: https://speakerdeck.com/nathansmith/960-grid-system


====================
Viewing the website
====================

Have a look at main.css to see the order in which the css files are included.

This ELIXIR website is in the folder docroot and in order to see the site without errors
the site should be opened in a server environment connected to the Internet as opposed
to directly clicking on individual html files to view in your browser. This is because
the site uses files that are not local.

Local developers could use something like XAMPP or MAMP and set the disk location to the
docroot folder or rename docroot with the site name and place that (the renamed docroot)
in your htdocs folder.

XAMPP
https://www.apachefriends.org/index.html

MAMP
http://www.mamp.info


