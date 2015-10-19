This folder contains files of the structure and a quick quide that explains how to manipulate the following snippets:

- Static Slide


## Static Slide

Change the background-image by replacing the url of this line `<div class="slide" style="background-image:url('http://...');">`.

Inside of this tag `<div class="txt">` you will find the title represented by the tag `<h2></h2>`, and the descriptive text nested inside of `<div class="txt">` you can add `<br>` if wanted.


Uses: 
- `<h2>` Big & Regular type format (the title)
- `<div class="txt">` Regular & medium type format (the description)

```
<div class="slide" style="background-image:url('http://...');">
	<div>
		<div class="mask"></div>
		<div class="quote">
			<h2>SHAVE</h2>
			<div class="txt">
				Lorem ipsum dolor sit amet, consectetur adipiscing elit.<br>
				Nullam risus sapien, consectetur in diam eget
			</div>
		</div>
	</div>
</div>
```

![alt text](https://github.com/lindacastillor/motley_snippet_guide/blob/master/img/static_slide.jpg "Static Slide Example")