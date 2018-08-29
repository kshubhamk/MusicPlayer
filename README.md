# Music Player

**A material designed local music player for Android.**



# Pro Version
Under the GPLv3 License, users are allowed to modify and redistribute this software. 

## Download
You can find an apk file [here](https://drive.google.com/open?id=1ZOe9Bw1PsI2H3YmGEcHRu4fzxdpjttv4).

## Screenshots
[<img src="https://imgur.com/a/hVE2ix7" width=250>](https://imgur.com/a/hVE2ix7)

## Contribution
If you have any ideas or issues, don't hesitate to reach out to me. Every contribution is welcome.

## License
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

This application is Free Software: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.


## Do it yourself

1. Go to `/app/src/main/java/com/kabouzeid/gramophone/App.java`
2. Change the contents of this method:
```
public static boolean isProVersion() {
    return BuildConfig.DEBUG || 
    app.billingProcessor.isPurchased(PRO_VERSION_PRODUCT_ID);
}
```
&nbsp; &nbsp; &nbsp; &nbsp; To this:
```
public static boolean isProVersion() {
    return true;
}
```# Music-Player
