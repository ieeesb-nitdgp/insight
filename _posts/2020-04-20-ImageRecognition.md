---
layout: post
title:  "Teaching Computers to Understand Pictures"
author: Arindam
categories: [ Image Recognition, AI, ML, DL, Neural Networks, CNN ]
image: assets/images/imgrecog.png
wide_image: assets/images/imgrecog.png
thumb_image: assets/images/imgrecog.png
last_added: false
hidden: false
---
Let's look at two images to get started with:  

![](/assets/images/dog.jpg)  

![](/assets/images/tree.jpg)  

Ask yourself, what do these images show?  
It's not difficult to see that the first image is that of a 'dog' and the other one is that of a 'tree'!  
What if I argue, saying that the first image is that of a 'spacecraft' and the other one is of a 'house', XD!  
It's obvious that readers will disagree with me, but if I ask you to prove your claim, can you do that? Come on, should be trivial right! Come up with a solid proof to support your claim! I bet you can't do that. But, Why?  
Ever, thought of that? It's essentially because we just 'KNOW' these things and we have been taught to identify them accordingly, from a very young age! Humans have neither invented these nor discovered them. It's just that we all agree to call the object in the first image as a dog and the other one as tree!  
Now the billion dollar question is, can we pass over this 'KNOWLEDGE' to computers?  
Yes, why not, seems easy!  
Let's imagine we teach the computer in some language that it understands, that whenever you see something like the first image, print 'dog' as output!  
Eureka! mankind has just taught computers to identify dogs! Very well, now let's test the algorithm with this image as an input.  
![](assets/images/dog2.jpg)  
Trust me, even if the algorithm says that it's a dog with probability of 0.1, I'll be surprised. Pragmatically speaking, the algorithm will fail to even do that! But, why?  
Humans can do that easily, and we just taught a computer to do so! Why did the computer algorithm fail?  
The answer is simple and straightforward: You see, what we see as pictures with objects and other information, the computer sees the same as a bunch of numbers put in a matrix.  
Now, vaguely speaking, these numbers differed greatly in the two images and hence the computer couldn't identify correctly. The algorithm seems to be pretty dumb!!  
**A key takeaway here is that, we can't code computers explicitly to identify images!**  
Let's think in a different way; how does a child learn to identify objects? You see, a child captures images, roughly every 200 ms, since birth. So, by the time the child is three, he/she has seen millions of images already!  
This candid thought led to the creation of the largest database of images and opened up a challenge to the world (titled as, ImageNet Large Scale Visual Recognition Challenge). The idea was to come up with algorithms for identifying the images correctly. This dataset is referred to as 'ImageNet' and contains nearly 15 million images across 22,000 classes.  
images across 22,000 classes. The 'ImageNet' project was the brain-child of **Dr. Fei-Fei Li**.   
Take a look at this amazing talk: 
[How we teach computers to understand pictures | Fei Fei Li](https://www.youtube.com/watch?v=40riCqvRoMs)  
So far, we haven't talked anything about the so called 'algorithms' that manage to solve this convoluted problem of identifying images! Well, the ILSCVR Challenge was held every year from 2010 to 2017 and researchers (2012 -) managed to come up with different 'models' that went on reducing the classification error progressively. However, there's something, that all these models had in common: all of them were essentially Convolutional Neural Networks (CNN). CNNs were introduced long back by Yann Lecun in this paper. However, it was this challenge that popularized these networks and researchers started using them for different tasks such segmentation, image enhancement and many more!  
The ILSCVRC 2012, saw the introduction of a 'Deep network' called ALexNet which improved error rates from 25% to 16% on the ImageNet dataset and thus marked the beginning of the Deep Learning Era!  
## So what is Classification?  
Classification is essentially predicting a label (in probabilistic terms) for an input image. Something like this:  
![](/assets/images/flowerclass.png)  
Take a look at [The Complete Beginner's Guide to Deep Learning: Convolutional Neural Networks and Image Classification](https://towardsdatascience.com/wtf-is-image-classification-8e78a8235acb)  
## Unleashing the Power of DEEP LEARNING  
Let's talk about one of my favourite applications of deep learning here: **Defocus Image Deblurring**  
I'm sure that all of us have taken pictures like these, especially when travelling on a fast moving vehicle:  
![](/assets/images/haze.png)  
This is what Deep Learning based frameworks can do to this image:  
![](/assets/images/fixhaze.png)  
Another super interesting application of DL is Image Impainting:  
Let's look at an image that's been fiddled with, something like  
![](/assets/images/fiddledimg.png)  
We surely want the image back! No issues, DL can always be called to rescue, and it gives us  
![](/assets/images/fixfiddle.png)  
There are tons of different applications of DEEP LEARNING and if you want to get started with CNNs, take a look at this video:  
[A friendly introduction to Convolutional Neural Networks and Image Recognition](https://www.youtube.com/watch?v=2-Ol7ZB0MmU)  
However, if you are looking at some specific courses on Deep Learning (and wish to work with me on some specific applications), take a look at the courses on **Udemy**.