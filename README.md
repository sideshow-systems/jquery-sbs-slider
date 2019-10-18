# jquery-sbs-slider

[![npm (scoped)](https://img.shields.io/badge/npm-v0.2.1-brightgreen.svg)](https://github.com/sideshow-systems/jquery-sbs-slider)
[![npm (scoped)](https://badgen.net/packagephobia/install/@sideshowsystems/jquery-sbs-slider)](https://packagephobia.now.sh/result?p=%40sideshowsystems%2Fjquery-sbs-slider)

jQuery SideBySide Slider


#### Package Managers

```sh
# NPM
npm install @sideshowsystems/jquery-sbs-slider
```

#### Usage

HTML
```html
<div class="img_sbs_box">
	<div class="imgwrapper imgleft">
		<img src="image-left.jpg" />
	</div>
	<div class="imgwrapper imgright">
		<img src="image-right.jpg" />
	</div>
</div>
```

Java Script
```js
$('.img_sbs_box').sbsbox();
```

with options
```js
$('.img_sbs_box').sbsbox({
	showPcnt: 90
});
```

#### Settings

Option | Type | Default | Description
------ | ---- | ------- | -----------
aniSpeed | int | 250 | Animation speed in milliseconds
showPcnt | int | 85 | Percentage of image reveal