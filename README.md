# Simple SVG Icons

I've come to really enjoy the simplicity of inline SVG icons. This repository will serve as a home for the icons I create for my various web projects. All icons are 30x30. Enjoy!

<br>

![](https://rawgit.com/dotspencer/simple-svg-icons/master/icons/play.svg)| Play
---|---

```html
<svg height="30" width="30" xmlns="http://www.w3.org/2000/svg">
  <polygon points="5,0 25,15 5,30"/>
</svg>
```
---

![](https://rawgit.com/dotspencer/simple-svg-icons/master/icons/pause.svg)| Pause
---|---

```html
<svg height="30" width="30" xmlns="http://www.w3.org/2000/svg">
  <rect height="30" width="8" x="3"/>
  <rect height="30" width="8" x="17"/>
</svg>
```
---

![](https://rawgit.com/dotspencer/simple-svg-icons/master/icons/restart.svg)| Restart
---|---

```html
<svg height="30" width="30" xmlns="http://www.w3.org/2000/svg">
	<defs>
		<mask id="m">
			<rect height="30" width="30" fill="white" />
			<circle cx="15" cy="15" r="7" fill="black" />
			<polygon points="0,15 15,15 0,26" fill="black"/>
		</mask>
	</defs>
  <circle cx="15" cy="15" r="13" mask="url(#m)" />
  <rect height="10" width="5" y="3" fill=""/>
  <rect height="5" width="13" y="12" fill=""/>
</svg>
```
---

![](https://rawgit.com/dotspencer/simple-svg-icons/master/icons/check.svg)| Check
---|---

```html
<svg height="30" width="30" xmlns="http://www.w3.org/2000/svg">
	<path d="M3 17 L12 24 L26 6" stroke="black" fill="none" stroke-width="6" />
</svg>
```
---

![](https://rawgit.com/dotspencer/simple-svg-icons/master/icons/modified.svg)| Modified
---|---

```html
<svg height="30" width="30" xmlns="http://www.w3.org/2000/svg">
	<circle cx="5" cy="15" r="3" />
	<circle cx="25" cy="15" r="3" />
	<circle cx="15" cy="15" r="3" />
</svg>
```
---

![](https://rawgit.com/dotspencer/simple-svg-icons/master/icons/download.svg)| Download
---|---

```html
<svg height="30" width="30" xmlns="http://www.w3.org/2000/svg">
	<rect height="4" width="26" x="2" y="24" />
	<rect height="8" width="4" x="2" y="18" />
	<rect height="8" width="4" x="24" y="18" />
	<path d="M15 2 V18" stroke="black" stroke-width="4" />
	<path d="M22 12 L15 19 L8 12" stroke="black" stroke-width="4" fill="none" />
</svg>
```
---
