<div>
  
<h1 align="center">
  <a href="https://github.com/moralistfestus/twicon-icon">
	Twicon icon - Amazing Fonts icons 🌟 
  </a>
</h1>

<p align="center">
  <strong>Twicon icon - The Amazing Font Icons for your unique designs/web projects.</strong><br>
	Twicon icon is an Open Source Icons (Completely free) that renders svg formatted codes into icons to give your projects a great look. 
</p>

<p align="center">
 
<a href="https://github.com/MoralistFestus/twicon-icon/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="This repository is released under the MIT license." />
  </a>
  
  <a href="https://github.com/MoralistFestus/twicon-icon/blob/master/CONTRIBUTING.md">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome!" />
  </a>
</p>

<h3 align="center">  
  <a href="https://www.developercircleresources.com/learningPath/open-source">Learn the Basics</a>
  <span> · </span>
  <a href="https://github.com/MoralistFestus/twicon-icon/blob/master/CONTRIBUTING.md">Contribute</a>
  <span> · </span>
  <a href="https://twitter.com/moralistfestus">@moralistfestus</a>
  <span> · </span>
  <a href="https://facebook.com/moralist.festus">Moralist Festus</a>
  <span> · </span>
  <a href="https://github.com/MoralistFestus">@MoralistFestus - Github</a>
</h3>

</div>

---

<br />

## Contents - Documentation

### 🚀 Basic Usage
<br />

### CDN
```html
    <!-- Releases by tagged name -->
   <!-- not recommended for production purposes -->
https://cdn.jsdelivr.net/gh/MoralistFestus/twicon-icon/css/twicon.css
   
   <!-- Changes with Minor releases -->
https://cdn.jsdelivr.net/gh/MoralistFestus/twicon-icon@0.1.1/css/twicon.css
  
   <!-- Changes with Minor releases -->
https://cdn.jsdelivr.net/gh/MoralistFestus/twicon-icon@1.1.1/css/twicon.css

   <!-- Changes with Major releases - recommended -->
https://cdn.jsdelivr.net/gh/MoralistFestus/twicon-icon@1.2.1/css/twicon.css

   <!-- Recommended for production purposes - latest release -->
https://cdn.jsdelivr.net/gh/MoralistFestus/twicon-icon@1.3.2/css/twicon.css

   <!-- Recommended for production purposes - latest release (include all.css) -->
https://cdn.jsdelivr.net/gh/MoralistFestus/twicon-icon@1.3.2/css/all.css

```

### CDN - Animation
```html
https://cdn.jsdelivr.net/gh/MoralistFestus/twicon-icon@1.3.2/css/animation.css
```
All e.g(`.css` file) is followed by a minfied version (`.min.css` file) for each respective files.
We recommend you use the **all.css** or **all.min.css**.

The twicon icons Component is an easy and performant way to use twicon in your app. The component will dynamically load an SVG for each icon, so your app is only requesting the icons that you need. For example:

```html
  <!-- generate home 🏡 icon -->
	<i class="twicon-home"></i>
```



### ⚡ Variant
 

<br />

Each app icon in twicon has a/an `empty`, `squared` `border` `border-circle` and `circled` variant. These different variants are provided to make your web/app feel native to a variety of platforms. The filled variant uses the default name without a suffix. 

```html
<!-- generating different variants for icons -->
	<i class="twicon-camera"></i>
        <!-- circled variant -->
	<i class="twicon-info-circled"></i>
        <!-- squared variant -->
	<i class="twicon-facebook-squared"></i>
        <!-- empty variant -->
	<i class="twicon-heart-empty"></i>
        <!-- border variant -->
	<i class="twicon-css3 twicon-border"></i>
        <!-- border-circle variant -->
	<i class="twicon-html3 twicon-border-circle"></i>
```


### 🌟 Size 

<br />

To specify the icon size, you can use the `twicon-size` attribute for our pre-defined font sizes.

```html
      <!-- specifying sizes for icons -->
        <!-- 5x icon size -->
	<i class="twicon-home twicon-5x"></i>
        <!-- 4x icon size -->
	<i class="twicon-camera twicon-4x"></i>
        <!-- 3x icon size -->
	<i class="twicon-meetup twicon-3x"></i>
        <!-- 2x icon size -->
	<i class="twicon-facebook-squared twicon-2x"></i>
        <!-- large icon size -->
	<i class="twicon-heart-empty twicon-lg"></i>
        <!-- normal icon size -->
	<i class="twicon-twitter"></i>
```

Or you can set a specific size by applying the `font-size` CSS property on the `.twicon` class component. It's recommended to use pixel sizes that are a multiple of 8 (8, 16, 32, 64, etc.)

```css
.twicon {
  font-size: 64px; /* your icon size */
}
```


### 🎨 Colors
  
<br />

Few inbuilt colors are available for use. You need to add the color attribute to the icon like `.dark`.

The following colors are available:
basic, secondary, danger, gold, cool, soft, light, dark, vital

```html
	<!-- specifying icon colors -->
	     <!-- dark color -->
	<i class="twicon-github twicon-5x dark"></i>
	     <!-- vital color -->
	<i class="twicon-twitter twicon-5x vital"></i>
```

Specify your own icon color by applying the `color` CSS property on the `.twicon` class component.

```css
.twicon {
  color: blue;
}
```

### 🎉 Postitioning

<br />

Specify Icon position by applying the `pull-left` or `pull-right` class component.

```html
<!-- Specifying icon positions, pull left and right positioning -->
        <!-- pull right -->
	<i class="twicon-download pull-right"></i>
	    <!-- pull left -->
	<i class="twicon-download pull-left"></i>
```

### 🎆 Rotating 

<br />

To use the rotate features of Twicon amazing icons. Include the **animation.css** file in your html file or by CDN;

```html
https://cdn.jsdelivr.net/gh/MoralistFestus/twicon-icon@1.3.2/css/animation.css
```

Specify Icon rotation by applying the inbuilt `twicon-rotate-` class component.

```html
		<!-- specifying icon rotation by percent -->
				<!-- rotate 45% -->
	<i class="twicon-camera twicon-5x twicon-rotate-45"></i>
				<!-- rotate 90% -->
	<i class="twicon-meetup twicon-5x twicon-rotate-90"></i>
				<!-- rotate 180% -->
	<i class="twicon-smile twicon-5x twicon-rotate-180"></i>
				<!-- rotate 270% -->
	<i class="twicon-whatsapp twicon-5x twicon-rotate-270"></i>
			  <!-- rotate flip-vertical -->
	<i class="twicon-heart twicon-5x twicon-flip-vertical"></i>
		     <!-- rotate flip-horizontal -->
	<i class="twicon-comment twicon-5x twicon-flip-horizontal"></i>
```

Also, the **animation.css** contains basic animation function.
Specify animation function by applying the `animate-spin` class component. E.g 👇

```html
           <!-- animation spin component -->
	<i class="twicon-camera twicon-5x animate-spin"></i>
```


### 🌌 Versions 
<br />

Twicon latest release is **v1.3.2** - recommended for development and production purposes. 

### Older versions
- v0.1.1
- v1.1.1
- v1.2.1

Need older versions of twicon, check the releases section to get the older versions based on tagged version.


### 👐 Contributing
  
<br /> 

Interested to contribute to this open source project, Please read the [Contributing Guidelines](./CONTRIBUTING.md) 
Thanks for showing interesting in using Twicon Icon. Do share with other developers.!
</details>


## License

Twicon Amazing Icon is [MIT licensed](./LICENSE).
