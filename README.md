# Easy Themes for ProtonMail

This is a collection of simple color themes for the [ProtonMail](https://protonmail.com/) web app. 🎨

&nbsp;

## Dark Theme
<img src="https://amdelamar.com/pm-theme/screenshots/dark-screenshot-3.12.41.png" width="100%" />

[Copy the CSS directly](/themes/pm-dark-theme.min.css) and [edit the colors](#customize).

&nbsp;

## Flat Theme
<img src="https://amdelamar.com/pm-theme/screenshots/flat-screenshot-3.12.41.png" width="100%" />

[Copy the CSS directly](/themes/pm-flat-theme.min.css) and [edit the colors](#customize).

&nbsp;

## Background Image Theme
<img src="https://amdelamar.com/pm-theme/screenshots/bg-image-screenshot-3.12.41.png" width="100%" />

[Copy the CSS directly](/themes/bg-image-theme.min.css) and [edit the image](#customize) variable `--image` to your own image.
Take a look at [coolbackgrounds.io](https://coolbackgrounds.io/) for awesome backgrounds.

&nbsp;

## GM Theme
<img src="https://amdelamar.com/pm-theme/screenshots/gm-screenshot-3.12.41.png" width="100%" />

[Copy the CSS directly](/themes/gm-theme.min.css) and [edit the colors](#customize).

&nbsp;

## Customize

Take any theme above and you can override the theme colors with your own.

```css
/* First paste the CSS theme. */

/* Now you can change the colors... */
:root {
    --theme1: #3652d1; /* Blue instead of Red */
}
```

And that's it!

CSS `variables` make it easy to override colors. The `root` keyword just means it will set the variables globally. These themes have been simplified down into **7 "core" colors** that make it easy to overwrite any colors of your choice. So take one of the themes above and set the colors with your own. You can also generate a pretty [color palette here](https://coolors.co/).

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
- If you're trying to use `@import`, the Content-Security-Policy (CSP) header blocks `@import` statements from loading remote content. To get around this, please copy and paste the entire contents of the CSS theme rather than the `@import` line.

## Privacy and Performance

~~The above code used a CSS `import` statement for ease of use and quickly trying out a theme. However, the CSS `import` statement causes files to load sequentially instead of parallel, thus slowing down your pages load performance. Also, if your privacy is of the utmost importance, then I wouldn't use the CSS `import` statment from above. It potentially could reveal your behavior e.g. identifying *when* you load up ProtonMail using *which* specific theme. To avoid this, please copy & paste the entire contents of the CSS file, rather than use the `import` statement.~~ This is no longer a concern, now that the Content-Security-Policy (CSP) Header blocks `@import` statements from loading remote content.

## Contribute

Spot a problem or bug? You can open an [issue here](https://github.com/amdelamar/pm-theme/issues).

I'll accept pull requests to the `master` branch too. Please make sure to minify the CSS as well.

## Share with friends

- Copy, edit, and share any of these themes.
- Licensed as [MIT](/LICENSE.md) and *free forever*.
