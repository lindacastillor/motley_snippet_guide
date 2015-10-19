This folder contains files of the structure and a quick quide that explains how to manipulate the following snippets:

- Static Slide
- Grid of Profiles Images

------


## Static Slide

The first element that you will find is the static slide `<div class="slide" style="background-image:url('http://...');">` which it works to display a short description with a background-image.

Change the image by replacing the url of this line `<div class="slide" style="background-image:url('http://...');">`.

Inside of this tag `<div class="txt">` you will find the title represented by the tag `<h2></h2>`, and the descriptive text nested inside of `<div class="txt">` where you can add anchors if required.


Uses: 
- `<h2>` Big & Regular type format (the title)
- `<div class="txt">` Regular & medium type format (the description)

```
<div class="slide" style="background-image:url('http://...');">
	<div>
		<div class="mask"></div>
		<div class="quote">
			<h2>AMBASSADORS</h2>
			<div class="txt">
				Interested to becoming an Ambassador? <a href="mailto:inquire@themotley.com">Tell us why </a>
			</div>
		</div>
	</div>
</div>
```

![alt text](https://github.com/lindacastillor/motley_snippet_guide/img/static_slide_ambassadors.jpg "Text and Image Example")


## Grid of Profiles Images

Place the next line on the markup `<div class="category_cont">`. 

Change the anchors and replace url images. To edit the caption of the image replace the text inside of the `<h1>` tag.


Uses:
- Upgrade the image url
- `<h1>` Caption of the image

```
<figure>
	<a href="http://...">
		<img src="http://..">
		<figcaption>
		<h1>THE DAPPER DUDE</h1>
		</figcaption>
	</a>
</figure>
```

![alt text](https://github.com/lindacastillor/motley_snippet_guide/img/ambassadors.jpg "Text and Image Example")