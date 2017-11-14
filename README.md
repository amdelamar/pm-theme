<img src="https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fcache3.asset-cache.net%2Fxt%2F171555439.jpg%3Fv%3D1%26g%3Dfs1%7C0%7CEPL%7C55%7C439%26s%3D1&f=1" align="right" />

# Easy Themes for ProtonMail

A collapsed CSS that's simple to edit colors and share.

&nbsp;

## Dark Theme
<img src="https://austindelamar.com/pm-theme/screenshots/dark-screenshot-3.12.png" width="100%" />

```css
/* Copy this line into ProtonMail's custom theme box: */
@import url("https://austindelamar.com/pm-theme/themes/pm-dark-theme.min.css");
```
Or [copy the CSS here](/themes/pm-dark-theme.min.css) and [edit the colors](#customize).

&nbsp;

## Flat Theme
<img src="https://austindelamar.com/pm-theme/screenshots/flat-screenshot-3.12.png" width="100%" />

```css
/* Copy this line into ProtonMail's custom theme box: */
@import url("https://austindelamar.com/pm-theme/themes/pm-flat-theme.min.css");
```
Or [copy the CSS here](/themes/pm-flat-theme.min.css) and [edit the colors](#customize).

&nbsp;

## GM Theme
<img src="https://austindelamar.com/pm-theme/screenshots/gm-screenshot-3.12.png" width="100%" />

```css
/* Copy this line into ProtonMail's custom theme box: */
@import url("https://austindelamar.com/pm-theme/themes/gm-theme.min.css");
```
Or [copy the CSS here](/themes/gm-theme.min.css) and [edit the colors](#customize).

&nbsp;

## Customize

Take any theme above and you can override the theme colors with your own.

```css
/* First load the theme. */
@import url("https://austindelamar.com/pm-theme/themes/gm-theme.min.css");

/* Now you can change the colors... */
:root {
    --theme1: #3652d1; /* Blue instead of Red */
}
```

And that's it!

CSS `variables` make it easy to override colors. The `root` keyword just means it to set the variables globally. This CSS-only theme has been condensed down into **7 "core" colors** that make it very simple to use any colors of your choice. So take one of the themes above and overwrite these colors with your own. You can generate a pretty [color palette here](https://coolors.co/).

```css
:root {
/* Core Theme Colors */
    --theme1: #66669a; /* Purple */
    --theme2: #5f5f60; /* Dark Grey */
    --theme3: #f0f0f0; /* Light Grey */
    --theme4: #bcbdbf; /* Grey */
    --theme5: #797a7c; /* Medium Grey */
    --theme6: #9397cd; /* Light Purple */
    --theme7: #fefefe; /* White */
}
```

1. Copy a CSS theme.
1. Paste in ProtonMail. `Settings` > `Appearance` > `Custom Theme`.
1. Customize the colors (or leave default).
1. Enjoy!

## Notes

- This is only available for the WEB version and not the MOBILE app.
- Some of these themes aren't always the best. **If you have any problems** you can open an [issue here](https://github.com/amdelamar/pm-theme/issues).

## Privacy and Performance

The above code used a CSS `import` statement for ease of use and quickly trying out a theme. However, the CSS `import` statement causes files to load sequentially instead of parallel, thus slowing down your pages load performance. Also, if your privacy is of the utmost importance, then I wouldn't use the CSS `import` statment from above. It potentially could reveal your behavior e.g. identifying *when* you load up ProtonMail using *which* specific theme. To avoid this, please copy & paste the entire contents of the CSS file, rather than use the `import` statement.

## Contribute

Spot a problem or bug? You can open an [issue here](https://github.com/amdelamar/pm-theme/issues).

I'll accept pull requests to the `master` branch too. Please make sure to minify the CSS as well.

## Share with friends

- Save, copy, tweak, and share any of this CSS theme.
- Licensed as [MIT](/LICENSE.md) and *free forever*.
