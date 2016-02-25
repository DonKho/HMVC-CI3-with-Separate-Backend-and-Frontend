Module separation for back-end and front-end using HMVC and template separation using template libraries

I am using two third party libraries, you can find it in zip file.

1. HMVC for modular developed by wiredesignz
2. Template engine for templating by Phil Sturgeon

Just unzip it into your webserver root directory and run

http://localhost/{foldername} for front-end

and 

http://localhost/{foldername}/admin for back-end

application/modules/back, it is for the back-end modules
application/modules/front, it is for the front-end modules

similarly
modules/layouts/back for the back-end templates
modules/layouts/front for the front-end templates

assets/admin for the back-end themes
assets/front for the front-end themes
assets/lib for libraries/plugins like bootstrap and jquery

Nothing hacked in original code just configured using config.php and index.php
Original folder structures by Bhuban <bhuban@gmail.com>, I just updated some of the directories
and index.php files for my own structures and my project. If you found this useful, please share.
For any suggestion and comments you can reach me at jmtolibas@hotmail.com

Enjoy coding!