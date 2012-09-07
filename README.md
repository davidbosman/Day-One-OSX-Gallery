Day-One-OSX-Gallery
===================

This a *dirty* hack to display Day One's photos on OS X in an HTML page, in a similar view as the iOS version of the app. 

It's a very simple shell script (+ a few css style) that looks into iCloud's files to find DayOne pictures. 

If you use Dropbox instead, change `PATH2ENTRY=` value to reflect the path to your DayOne photos folder. Something like **~/Dropbox/Apps/Day\ One/Journal.dayone/photos**.

If you don't like command line, the Automator Services should work fine (unzip it and save it under **~/Libray/Services**).

Tested under Mountain Lion 10.8.1.

More info (in French), here : [Galerie photos Day One sous OS X](http://davidbosman.fr/blog/2012/09/07/galerie-photos-day-one-sous-os-x/).