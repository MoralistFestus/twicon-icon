# Twicon icons

[twicon](http://twicon.github.io/) is a completely open-source icon set with 800+ icons crafted for web, iOS, Android, and desktop apps. Twicon icon was built for [Twinkle css Framework](https://twinklecss.com/), so icons have both Material Design and iOS versions.

This icons can applied in your projects to give your project a beautiful looking icons, twicon icons comes with a lot of inbuilt functionalities to make your great icon looks.

Note: This icons are subjected to copyright licenses and this icon should not be modified or reuse without the subjugal consent or permission from the author or co-contributors. 

We intend for this icon pack to be used with [twinklecss](http://twinkless.com/), but it’s by no means limited to it. Use them wherever you see fit, personal or commercial. They are free to use and licensed under [MIT](http://opensource.org/licenses/MIT).


## Contributing

Thanks for your interest in contributing! Read up on our guidelines for
[contributing](https://github.com/twicon-team/twicon/blob/master/.github/CONTRIBUTING.md)
and then look through our issues with a [help wanted](https://github.com/ionic-team/ionicons/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22)
label.


## Using the icon 

The twicon icons Component is an easy and performant way to use twicon in your app. The component will dynamically load an SVG for each icon, so your app is only requesting the icons that you need.


### Installation

If you're using [twicon Framework](https://github.com/programmerFestus/twinklecss),  clone or download from the github repository, twicon is packaged by default, so no installation is necessary. Want to use twicon icons with twinkle css Framework? 
clone the icon [here](https://github.com/programmerFestus/twicon-icon)

### Including twicon in your projects

To use twicon icons in your projects, you have to set the file path or directory to the `twicon.css` file in the css folder. Or copy this folder to your projects directory and include:

```html
   	<link rel="stylesheet" type="text/css" href="css/twicon.css"/> 
```
or

```html
   	<link rel="stylesheet" type="text/css" href="pathtofile/css/twicon.css"/> 
```
or use the minified version which is twicon.min.css

### Basic usage

To use a built-in icon from the twicon package, follow this guidelines: to use the icon use `twicon-name'
the name specify the name for the icon you want to generate:

```html
<i class="twicon-home"></i>
```

this will generate home icon.


## Variants
Each app icon in twicon has a/an `empty`, `squared` `border` `border-circle` and `circled` variant. These different variants are provided to make your web/app feel native to a variety of platforms. The filled variant uses the default name without a suffix. 

```html
<i class="twicon-camera"></i> 
<i class="twicon-info-circled"></i>
<i class="twicon-facebook-squared"></i>
<i class="twicon-heart-empty"></i>
<i class="twicon-css3 twicon-border"></i>
<i class="twicon-html3 twicon-border-circle"></i>
```

## Size

To specify the icon size, you can use the `twicon-size` attribute for our pre-defined font sizes.

```html
<i class="twicon-home twicon-5x"></i>
<i class="twicon-camera twicon-4x"></i>
<i class="twicon-meetup twicon-3x"></i>
<i class="twicon-facebook-squared twicon-2x"></i>
<i class="twicon-heart-empty twicon-lg"></i>
<i class="twicon-twitter"></i>
```

Or you can set a specific size by applying the `font-size` CSS property on the `.twicon` class component. It's recommended to use pixel sizes that are a multiple of 8 (8, 16, 32, 64, etc.)

```css
.twicon {
  font-size: 64px; /* your icon size */
}
```

## Color

Specify the icon color by applying the `color` CSS property on the `.twicon` class component.

```css
.twicon {
  color: blue;
}
```
Few inbuilt colors are available for use. You need to add the color attribute to the icon like `.dark`.

The following colors are available:
basic, secondary, danger, gold, cool, soft, light, dark, vital

```html
<i class="twicon-github twicon-5x dark"></i>
<i class="twicon-twitter twicon-5x vital"></i>
```


## Stroke weight
When using an `outline` icon variant it is possible to adjust the stroke weight, for improved visual balance relative to the icon's size or relative to the weight of adjacent text. You can set a specific size by applying the `--ionicon-stroke-weight` CSS custom property to the `.twicon` component. The default value is 32px.

```html
<i class="twicon-camera"></i>
```

```css
.twicon {
  --twicon-stroke-width: 16px;
}
```

## What Version

Currently twicon icon's current version is `v0.1.1`, progressive updates will be made to the icons
to and progressive stable versions will be released in as much as the icons are under development, and
will be made available for production and development purposes.

## Versions

version 0.1.0 (old) supports 400+ icons
version 0.1.1 (new) supports 800+ icons

## License

twicon is licensed under the [MIT license](http://opensource.org/licenses/MIT).

## Support Twicon icon

You can support the development of twicon icon fonts by sharing the repository to others and introducing to developers how
it works, star this repository and fork it and then share. You're free to make an article partaking to the development of twicon
icon and such action will be greatly appreciated. 

## Related
Developer's Portfolio: <a href="https://moralistdev.000webhostapp.com">Website</a>