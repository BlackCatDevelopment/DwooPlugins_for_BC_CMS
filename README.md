Here you will find some optional Dwoo Plugins for BlackCat CMS (https://github.com/webbird/LEPTON_2_BlackCat)

###General usage:###
Copy the files you want to use to /modules/lib_dwoo/dwoo/plugins/personal/ in your BlackCat CMS installation. Done.

###Current plugins:###

* MakeThumb

####Description####
A plugin to create jpg-thumbnails of images in /temp/media/

####Usage:####
{makeThumb( [link to file on your server], [optional prefix for files (default '')], [width (default 200)], [height (default 300)], [quality of jpg (default 90)])}

<strong>Example</strong>
>{makeThumb( '/media/example.png', 'thumb_', 48, 48, 75 )}
