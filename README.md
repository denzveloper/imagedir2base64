# imagedir2base64 (PHP+Codeigniter)
Get image on a directory then optimize to Webp 70% quality (chrome based browser) or jpeg 80% quality (other based browser) and encode to base64


just call this file then call function with directory.

ex: show('/assets/path/to/image.png')


Tested on system: Manjaro Linux, php73, Apache, Codeigniter

*Maybe load page longer than usual because waiting for render image first*

# How to Install (Codeigniter)?
1. Move all to Library 
2. Config (ajust index.png and notfound.png directory)
3. Call library + Function
4. move index.png and notfound.png
5. Run!

_other library or using native php doesnt support by me. but you can modify it to run other framework/navive php_
