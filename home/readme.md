This folder contains files of the structure and a quick quide that explains how to manipulate the following snippets:

- Slideshow
- Slideshow Tabs
- Half Blocks

------


## The Slideshow
------

To get started you need to identify and make sure that you're editing inside this tag `<ul class="rslides slide" id="slider1">`

The following snippet is a sample that compose one slide element, in here you will be able to change the image by replacing the url of this line `<li style="background-image: url('PASTE_URL_HERE');">`

Next you have the `<div class="quote">` where specifically you will need to write inside the `<p></p>` tag or the `<h2></h2>` tag to have the predeterminated styles for the short description.

Uses: 
- <p> Small Italic format
- <h2> Big Regular format

```
<li style="background-image: url('http://...');">
	<div class="mask">&nbsp;</div>
	<div class="quote">
		<p>TRY OUR</p>
		<h2>BABY FACE</h2>
		<p>RECOMMENDED SHAVING</p>
		<h2>KITS</h2>
	</div>
</li>
```

![alt text](https://github.com/lindacastillor/motley_snippet_guide/img/slider.jpg "Text and Image Example")


## Slideshow Tabs
------

Place at this line on the markup `<ul class="slider-pager" id="slider3-pager">`. 


Edit the text inside of this tags `<p>` & `<h1>`, the anchors `<a href="#tab1">` are related to the id of the slides so you can trigger them to related slide, they can stay how they are, it's not necessary to replace the anchor.

Uses:
- <p> Uppercase Italic type format
- <h1> Uppercase Regular type format

```
<li>
	<a href="#tab1">
		<p>New in store</p>
		<h1>travel bags</h1>
	</a>
</li>
```

![alt text](https://github.com/lindacastillor/motley_snippet_guide/img/slider_tabs.jpg "Text and Image Example")


## Half Blocks
------

Locate the next tag `<div class="main_gal">` now follow the next steps to alternate between *only image*, *image & text*, *only text*.

##### Only Image Block

Sample to display only image block by just replacing the url on the `<div class="img">`, don't forget to upgrade the link in the anchor tag if necessary `<a href="">`.

Uses:
- <a href="#"> Modify the url
- Change the background-image 

```
<li>
	<a href="#">
		<div class="img" style="background-image:url('http://...');"></div>
	</a>
</li>
```

![alt text](https://github.com/lindacastillor/motley_snippet_guide/img/only_image.jpg "Text and Image Example")

##### Image & Text Block

Use the next snippet to have a block with a small description overlaping a background image. 

Uses:
- Change the url of the image
- <a href="#"> Modify the url
- <h2> Italic type format
- <p> Regular type format

```
<li>
	<a href="#">
		<div class="active">
   			<h2>Superior Grooming</h2>
   			<p> 3 Moisturizing Must Haves For Fighting Summer Shine</p>
		</div>
		<div class="img_mask" style="background-image:url('http://...');"></div>
	</a>
</li>
```
![alt text](https://github.com/lindacastillor/motley_snippet_guide/img/text_and_image.jpg "Text and Image Example")

##### Only Text Block

This sample will help you display the text format.

Uses:
- <a href="#"> Modify the url
- <h2> Regular & meduim size type format (title text)
- <p> Regular & small size type format (description text)
- <span> Italic & medium size type format (subject text)

```
<li>
	<a href="#">
		<div class="white_txt">
			<h2>Superior Grooming.</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing
			elit. Vivamus viverra venenatis ornare.
			Etiam ut sem nec dolor vestibulum eleifend.
			Vivamus viverra venenatis ornare. Etiam ut sem
			nec dolor vestibulum eleifend.</p>
			<span>Shop Now.</span>
		</div>
	</a>
</li>
```

![alt text](https://github.com/lindacastillor/motley_snippet_guide/img/only_text.jpg "Text Example")