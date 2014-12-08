jQuery-Gallery
==============
This plugin will allowed you to create a gallery.

- Use data-gallery for each gallery you want.
- Each time you name your data-gallery differently you will get a new gallery.
- Do not use the same src picture twice (this is kinda buggy).
- You can set a speed for animations (by default: 300).
- You can use the css file by default or create your own an rename the classes.
- It is under MIT licence.

This will call the plugin:
	`$(document).jquerygallery();`

Demo:
--------
View a [demo here](http://www.guillaumebreux.com/git-plugin/gallery "jQuery-Gallery")
Others options:
--------
- `'coverImgOverlay' : true,` *If you want thumbnails under your picture*
- `'thumbnail' : "coverImgOverlay",` *This is the name of the class that contain thumbnails*
- `'thumbnailHeight' : 120,` *Set an height value to center the picture vertically*
- `'imgActive' : "imgActive",` *This is the name of the main classe that contain the pictures of each galleries*
- `'overlay' : "overlay",` *This plugin will create a class called "overlay", you can change de name*
- * *You can change the actions pictures, i used fontAwesome.*
	* `'imgNext' : "<i class="fa fa-angle-right"></i>",` *Change the duration of the smoothscroll*
	* `'imgPrev' : "<i class="fa fa-angle-left"></i>",` *Change the duration of the smoothscroll*
	* `'imgClose' : "<i class="fa fa-times"></i>",` *Change the duration of the smoothscroll*
- `'speed' : 300` *Finally, you can set the speed of animations.*


Look at the really sobre demo page, maybe that will help you to install this plugin.


