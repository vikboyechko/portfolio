# Portfolio Project

This project combined two weeks of diving deep into HTML and CSS.

What seemed simple at first turned into quite a complex webpage that uses responsive design, flex box, and grid, plus wireframing the plan of attack.

![Portfolio wide screengrab](/assets/images/portfolio-wide.png)

The website can be viewed here: [Vik Portfolio](https://vikboyechko.github.io/portfolio/)

## Challenges

One of the hardest parts was figuring out all the flex box and grid properties and values for three different layouts.

Another challenge was figuring out how to add a color overlay to images. It works with images loaded in the CSS using the background property, but I chose to load images in the HTML. What ended up working was using the CSS filter property to adjust brightness, hue rotation, and saturation, but it still doesn't look quite the same as a color overlay.

Finally, this website works great in Firefox, which is what I used for development, but it's not rendering correctly in Chrome or Safari. I'm not sure if this is a browser issue with supporting grid layout, or if each browser happens to load CSS elements slightly differently.