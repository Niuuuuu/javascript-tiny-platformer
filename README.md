HEADS UP:
=========
If running on Chrome, you may not be able to load the game, and get the following error when you view the console (press f12):

Cross origin requests are only supported for protocol schemes: http, data, chrome-extension, https, chrome-extension-resource.

POSSIBLE SOLUTIONS:

1) Run Chrome w/ security disabled (set specific flags mentioned below)
Link: http://stackoverflow.com/questions/24826544/chrome-allow-file-access-from-files-no-longer-working-was-using-to-see-webgl-th

2) Setup a simple python server (you need python installed)
Link: http://stackoverflow.com/questions/17351016/set-up-python-simplehttpserver-on-windows

3) Use Firefox or another browser

Solution #2 worked for me :)

4) Or you can set up the server using github, create a repo called username.github.io

For example : 

[Here](http://niuuuuu.github.io/javascript-tiny-platformer/)

Javascript Tiny-Platformer
==========================
A very minimal javascript platform game


Just a sinple example of how to have a tiny rectangle run around some rectangle platforms, 
collecting rectangular gold and avoiding rectangular monsters.

SUPPORTED BROWSERS
==================

Should work in any modern browser with canvas support

DEVELOPMENT
===========

The game is 100% client side javascript, html and css. It should run when served up by any web server.
