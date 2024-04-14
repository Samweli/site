---
layout: single
comments: true
title: Using AI in Trash Detection
published: true
---

![](https://raw.githubusercontent.com/samweli/jekyll-now/master/images/trash-detector.png)

_Trash detection web application interface_

## Building web application to detect trash in images

After trash mapping activity [here](http://samweli.github.io/Trash-Map/), some of the collected trash images didn't 
contain waste, this occured because some of the images were for legal dump sites.

During the collection activity the data wasn't tagged whether it contained illegal dump sites or legal dump sites or both.

So I built a simple web application that helps in detecting waste from an image. This was for a purpose of tagging images 
from the mapping activity whether they contain waste or not.

The result application can be found [here](http://trash-detection.herokuapp.com/).

I then ran the toool on all the image, and the result analysis can be seen in this [visualization](http://dar-trash-viz.herokuapp.com/)
under Analysis Menu with "Trash tagging" item.

A rough approximation on the tool is that 6 out of 10 images the tool did a right guess.


