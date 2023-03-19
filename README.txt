( )------{===================================================>

                   MINIMAL DUNGEON by 420AM

( )------{===================================================>

COMPATIBILITY: tested on Garlic OS 1.3.2

# INSTALLATION
- On partition containing 'CFW' folder, copy the 'CFW' folder
- On partition containing 'boot_logo.bmp', replace boot_logo.bmp for 1-bit style Anbernic orginal bootlogo

## IMAGE FORMATTING
- To format images to match this skin as intended (this will resize images onto left side, centered, and account for ~6px padding around the menu elements):
- Install ImageMagick: https://imagemagick.org/script/download.php
- Right click on your images folder, select 'Open powershell window here' then run the first script, followed by the second
- magick mogrify -resize "314x332" -gravity center -extent 314x332 -background transparent -flatten *
- magick mogrify -background transparent -gravity west -extent 634x454 -gravity west -splice 6x0 -gravity south -splice 0x26 *

### IF NO IMAGE FORMATTING
- Open 'settings.json' located in the 'skin' folder
- Modify the following 2 lines to match:
- "text-alignment": "center",
- "text-margin": 16,
- This will re-align the text back to center like the default skin

#### NOTES

- Unfortunately, I noticed a flaw in this skin, when hitting start to change the time/date/language this skin will produce black text on top of a mostly black background. If anyone knows a solution hit me up.
- I only have the english.json settings file to accomodate the font set at this time, if anyone is adapting for another language please send it my way and I will include in the official repository

##### ACKNOWLEDGEMENTS
- This skin was originally based off Platinum by Jason Scheirer (https://github.com/jasonbot/platinum-garlic)
- Font is [ChiKareGo](http://www.pentacom.jp/pentacom/bitfontmaker2/gallery/?id=3778)
- System logos are from [Express Mode](https://www.rg35xx.com/temas-garlicos/) and friends on [www.rg35xx.com](https://www.rg35xx.com/)
- Button icons are modified from [ansdor](https://ansdor.itch.io/button-icons)

( )------{===================================================>