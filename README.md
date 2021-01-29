# NodeRedCSS
Node Red Global CSS file in the form of UI template file with formatted text version for preview and a screenshot

This UI template sets up global styling for the rest of the NR app.  I hate material design, and prefer to go at it rogue and just make stuff I like.  I do not expect anyone to like what I did, but it shows how to style your own projects

This ui template file will be required for all the other NR flows I commit to Git.

This flow is dependant on  the following:

+ node-red-dashboard

I lumped all the images into this global repo.  You need to configure Node Red to serve up static resources.  For me, that meant creating a folder in my windows user directory like below and then copy all the resources into that folder.

+ C:/users/<your windows user here>/.node-red/static

Then you need to make sure you have configured the 'settings.js' file to point to that folder

+ httpStatic: 'C:/Users/<your windows user here>/.node-red/static'

Start here!

Disclaimer:

I have not fully "sanitized" any of these files.  Names, naming convention, formatting are all for my own use and do not adhere to any best practises or standard.

These files are for my own archiving purpose and being made available to anyone who wants to see a starter project for their own purpose. (Except usernames and passwords)

You can use these files for any private purpose you want.  No permission is given for commercial use.

If you find problems, do not expect me to implement fixes or maintain branches or multiple releases.  Feel free to modify the code as you see fit.  If you find something really egregious I would be interested in hearing about it even if I do nothing to fix it.  Call it a professional courtesy to simply share it back to me.

Erik Skyten
