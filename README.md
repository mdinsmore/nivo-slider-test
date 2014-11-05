Nivo Slider test site
=====================

A small project which allows you to embed gallery of images stored on github in a page on a google site.

Create you own version of this project
--------------------------------------

::

	Fork this project on to your github account.

	Add your own images to the images directory
	
	Edit the references to the images in index.html


Embed the site in your google site
----------------------------------

::

	Create a page to add the gallery
	
	Add a iframe to the page.  Currently you can do this by clicking on insert and then "more Gadgets".  Search for "Include gadget (iframe)"
	
	Configure the iframe as follow:
	
		url:  should be set to https://gitraw.com/<your user name>/<your respository name>/nivo-test/index.html
		e.g. https://rawgit.com/mdinsmore/nivo-slider-test/master/nivo-test/index.html
		Display scroll bar: No
		Width: <size of you pictures plus 50 pixels> e.g. 600 pixels
		Height: <size of your pictures plus 250 pixels> e.g. 600 pixels
		
		Uncheck all three checkboxes
		Dispaly : default
		
	Click ok to save to page and save page to view - you may need to play with the height and width to get that right.


