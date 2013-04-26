# Flatland

## About

Flatland is a simple theme and accompanying color scheme for Sublime Text 2. It is mostly derived from  [Soda](https://github.com/buymeasoda/soda-theme), the right place to start for any custom theme development for Sublime. Thanks Soda!

## Design

![Screen Shot!](https://raw.github.com/thinkpixellab/flatland/master/resources/screenshot.png)


## Installation
Clone into Sublime/Packages
**RENAME your flatline directory to Theme - Flatland**

### Manual Installation
You can also install it manually by following these instructions:

1. [Download theme files](https://github.com/thinkpixellab/flatland/archive/master.zip)
2. Unzip the files and copy the folder newly created folder into your Sublime Text 2 Packages directory with the name `flatland`. You can find that directory by selecting "Preferences > Browse Packages ...".
3. Activate the theme by modifying your user preferences to include the following:

```javascript
{
  "color_scheme": "Packages/Theme - Flatland/Theme - Flatland/Flatland.tmTheme",
  "theme": "Flatland.sublime-theme"
}
```

If you need help locating your user preferences file, you can find it selecting "Preferences > Settings - User".

## Optional Settings
The following options can be set in your user preferences:

```javascript
{
  // square file tabs instead of rounded corners
  "flatland_square_tabs": true,

  // Monokai theme (SublimeText's default) with Flatland background color
  "color_scheme": "Packages/flatland/Theme - Flatland/Flatland-Monokai.tmTheme"
}
```
