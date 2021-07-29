# PR Template to add a blog

Anyone submitting a PR should upload a screenshot of the first page as well ( which must include the cover photo).

Like this 
![image](https://user-images.githubusercontent.com/55195504/127500812-e47c9e06-533e-41bc-9039-0a407562e8b2.png)

Other than this, instructions for creating a blog post 

# Instructions

1. Always even number of articles (mostly last 2) should have *last_added* as *true*. 
2. thumb_image must have a dimension of *500px x 500px* 
3. wide thumb image must have a dimension of *1024px x 617px* 
4. Always at the beginning of a blog, there must be sentences and not any image. The wide_image is placed at the beginning of the blog post by default. So if there’s an image at the beginning, put it at the end of first paragraph.
5. In case of a photo and a caption use this format:
```
<div align="center">
	<img src="image_link"/>
</div>
<h6 style="text-align: center;">Image Caption</h6>
```

6. For adding links use this:
```
<a href="link target="_blank" style="overflow-wrap: anywhere;"> Text to show the link</a>
```

7. The title of the post is shown in ```<h1>``` at the top of the blog. So, there shouldn’t be any heading at the start of a blog. 
8. For any heading inside a blog use h3 instead of h1 or more precisely use 
```
“###” instead of “#”.
```
