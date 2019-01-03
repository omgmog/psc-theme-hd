## Playstation Classic HD theme

Like the default theme but with more definition...

### What is this?

It annoyed me how the default Playstation Classic theme contained such crappy icons and text. I know it's a _retro console_ but that doesn't mean it has to be near-unusable.

I've re-created most of the graphics.

I created [a script](https://github.com/omgmog/psc-theme-text-image-generator) to make generating text-based images faster (in all locales), and used Photoshop to diligently tackle everything else.

### How do I use this?

You need to have your Playstation Classic modded with _Bleemsync!_, and then your `boot.sh` or `lolhax.sh` needs to mount your theme directory from USB rather than then eMMC, e.g:

```
# Use custom theme
mount -o bind /media/theme/images/ /usr/sony/share/data/images/
mount -o bind /media/theme/sounds/ /usr/sony/share/data/sounds/
mount -o bind /media/theme/font/ /usr/sony/share/data/font/
```

Then grab the latest release of this theme from [here](https://github.com/omgmog/psc-theme-hd/releases) and extract it to your USB stick so that you have a `theme `directory containing all of the `images`, `font` and `sounds` directories.

![](https://i.imgur.com/S6hh7XE.png)

![](https://i.imgur.com/2OOywMR.png)

### Examples

Before:

![](https://i.imgur.com/gQrDGXL.png)
![](https://i.imgur.com/20dajD4.png)
![](https://i.imgur.com/fNm6YuL.png)

![](https://i.imgur.com/2U3rfdc.png)
![](https://i.imgur.com/Pkbqaro.png)
![](https://i.imgur.com/D2O349f.png)

After:

![](https://i.imgur.com/BsubrYU.png)
![](https://i.imgur.com/ROIAoRk.png)
![](https://i.imgur.com/QYnz3Mv.png)

![](https://i.imgur.com/rcgA5qQ.png)
![](https://i.imgur.com/hzCKEXY.png)
![](https://i.imgur.com/ThC4PF6.png)


And some photos of how it looks on-screen:

Before:

![](https://i.imgur.com/rNJoOwK.jpg)

After:

![](https://i.imgur.com/GiGD1aT.jpg)
