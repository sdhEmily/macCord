<h1 align="center">macCord</h1>
<p align="center">Pretty.</p>

# ![screenshot](https://raw.githubusercontent.com/sdhEmily/macCord/main/assets/preview.png)

## How to use

### Discord App

* BetterDiscord, Vencord, and Openasar users can grab the [macCord.theme.css](https://raw.githubusercontent.com/sdhEmily/macCord/main/macCord.theme.css) file and either
  * Place the file in the BetterDiscord or Vencord themes folder
  * Copy the text in the file, and paste it in Openasar's quick CSS text field
 
### Browser 
 * [![](https://img.shields.io/badge/install%20with-stylus-006666?style=flat-square)](https://github.com/sdhEmily/macCord/raw/main/macCord.user.css)

## Translucenty

<details>
<summary>Information on enabling translucency</summary>

### Check out [this issue](https://github.com/SlippingGittys-Discord-Themes/surCord/issues/42) if you use Windows. [Mica for Everyone](https://github.com/MicaForEveryone/MicaForEveryone) is known to play decently, but be very spotty.

This theme supports translucency. 

### You can achieve the same look on Vencord/macOS by doing as follows:

* Go to Settings > Vencord, then toggle "Enable Translucent Window".

![image](https://user-images.githubusercontent.com/76500838/231659229-4f261d16-304e-4904-b9f5-88478ab2fe89.png)


### Extra info
 * You can adjust the opacity and colors by pasting & messing with these varriables 
   
 ```css
 
.theme-dark {
  --background-tertiary: #2f31364b;
}

.theme-light {
  --background-tertiary: #ffffff1d;
}

```
</details>
 
## Extra info
<details>
<summary>Information about accents, themes, emoji, fonts, and more!</summary>

* You can very easily [change the accent color](https://cdn.discordapp.com/attachments/816373850647953439/984177819204603924/unknown.png) for macCord by navigating to `/src/_theming.scss` and [uncommenting **>>>one<<<**](https://github.com/SlippingGittys-Discord-Themes/macCord/blob/main/src/_theming.scss) of the accent colors.  
  
  BD and Stylus can uncomment these in macCord.theme.css / macCord.user.css

* Stylus users on Firefox have to be on version 102 or later and toggle "Patch CSP to allow style assets"  
  Chromium browsers shall be fine by default on any recent version.
  
  ![stylus setting](/assets/stylussettingneeded.png)
</details>


## Devs, Contributors, and other Creditors 

See [here.](https://github.com/sdhEmily/macCord/graphs/contributors)

