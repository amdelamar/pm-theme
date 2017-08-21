<img src="https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fcache3.asset-cache.net%2Fxt%2F171555439.jpg%3Fv%3D1%26g%3Dfs1%7C0%7CEPL%7C55%7C439%26s%3D1&f=1" align="right" />

# Easy Themes for ProtonMail

A collapsed CSS that's simple to edit by anyone.

### What's so special about this?

The CSS is collapsed down into **7 "core" colors** that make it very simple to change to any colors of your choice.

```css
:root {
/* Core Theme Colors */
    --theme1: #66669a;
    --theme2: #5f5f60;
    --theme3: #f0f0f0;
    --theme4: #bcbdbf;
    --theme5: #797a7c;
    --theme6: #9397cd;
    --theme7: #fefefe;
}
```
Take one of the themes below and overwrite these colors with your own. You can generate a pretty color palette from https://coolors.co/

&nbsp;

## PM Dark Theme
<img src="https://austindelamar.com/pm-theme/screenshots/pm-dark-theme.3.7.png" width="100%" />

```css
/* Copy this line into ProtonMail's custom theme box: */
@import url("https://austindelamar.com/pm-theme/themes/pm-dark-theme.css");
```
Or [copy the CSS here](/themes/pm-dark-theme.css) and [edit the colors](#customize).

&nbsp;

## PM Flat Theme
<img src="https://austindelamar.com/pm-theme/screenshots/pm-flat-theme.3.7.png" width="100%" />

```css
/* Copy this line into ProtonMail's custom theme box: */
@import url("https://austindelamar.com/pm-theme/themes/pm-flat-theme.css");
```
Or [copy the CSS here](/themes/pm-flat-theme.css) and [edit the colors](#customize).

&nbsp;

## GM Theme
<img src="https://austindelamar.com/pm-theme/screenshots/gm-theme.3.7.png" width="100%" />

```css
/* Copy this line into ProtonMail's custom theme box: */
@import url("https://austindelamar.com/pm-theme/themes/gm-theme.css");
```
Or [copy the CSS here](/themes/gm-theme.css) and [edit the colors](#customize).

&nbsp;

## Customize

Take any theme above and you can override the theme colors with your own.

```css
/* First load the theme. */
@import url("https://austindelamar.com/pm-theme/themes/gm-theme.css");

/* Now you can change the colors... */
:root {
    /* Blue instead of default GM Red */
    --theme1: #3652d1;
}
```

And that's it.

## Basic Usage

1. Copy a CSS theme.
1. Paste in ProtonMail. `Settings` > `Appearance` > `Custom Theme`.
1. Customize the colors (or leave default).
1. Enjoy!

## Notes

- This is only available for the WEB version and not the MOBILE app.
- Some of these themes aren't always the best. **If you have any problems** you can open an [issue here](https://github.com/amdelamar/pm-theme/issues).
- Older themes (Burnt, Gum, Seaweed) are still available [here](https://github.com/amdelamar/pm-theme/tree/master/themes).

## Privacy and Performance

The above code used a CSS `import` statement for ease of use and quickly trying out a theme. However, the CSS `import` statement causes files to load sequentially instead of parallel, thus slowing down your pages load performance. Also, if your privacy is of the utmost importance, then I wouldn't use the CSS3 import statment from above. It potentially could reveal behavior about you, identifying when and where you login to ProtonMail using a specific theme. To prevent these things from happening, please copy & paste the entire contents of the CSS file rather than use the `import` statement.

## Contribute

Have a theme you want to add? Or a nice set of colors? You can open an [issue](https://github.com/amdelamar/pm-theme/issues) and paste it. Or if you found a bug and want to report it you can do that too.

I'll accept pull requests to the `master` branch too.

## Share with friends

- Save, copy, tweak, and share any or all of this CSS code.
- Licensed as [MIT](/LICENSE.md) and free forever.
- Have fun!
