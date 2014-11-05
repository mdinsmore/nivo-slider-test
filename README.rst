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
	
	Add a iframe to the page.  Currently you can do this by clicking on insert
	and then "more Gadgets".  Search for "Include gadget (iframe)"
	
	Configure the iframe as follow:
	
		url:  https://rawgit.com/<your user name>/<your respository name>/index.html
		e.g. https://rawgit.com/mdinsmore/nivo-slider-test/master/index.html
	
		Display scroll bar: No
	
		Width: <size of you pictures plus 50 pixels> e.g. 600 pixels
	
		Height: <size of your pictures plus 70 pixels> e.g. 600 pixels
		
		Uncheck all three checkboxes
	
		Display : default
		
	Click "OK" to save to the page and then save page to view.
	You may need to tweak with the height and width to get that right.


