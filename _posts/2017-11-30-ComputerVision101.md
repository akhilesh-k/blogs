---
title:  "Computer Vision 101 - A Practical Guide to Start with Computer Vision"
header:
  teaser: "https://raw.githubusercontent.com/akhilesh-k/blogs/master/images/cv1.jpg"
categories: 
  - Computer Vision
tags:
  - Tutorial
comments: true
---

### A Practical Guide to Start with Computer Vision
> If We Want Machines to Think, We Need to Teach Them to See.
 <br>-Fei Fei Li, Director of Stanford AI Lab and Stanford Vision Lab.

**Why This Post??**<br>
As an undergraduate, I have fascinated, dreamed, worked and learnt much from Internet. We hear terms like Machine Learning, Computer Vision, AI..... everyday but how to actually get started with all these? This post is to introduce you to basics of Computer Vision.

The technology that makes machines such as computers or mobile phones see the surroundings is known as Computer Vision. Serious work on re-creating a human eye started way back in 50s and since then, we have come a long way. Computer vision has already made its way to our mobile phone via different e-commerce or camera apps.

Think of what more can be done by machine when they will be able to see as accurate as a human eye. Human eye is a complex structure and it goes through more complex phenomenon of understanding the environment. In a similar fashion, making machines see things and make them capable enough to figure out what they are seeing and further categorize it, is still a pretty tough job.

Working on Computer Vision is equivalent to working on millions of calculations in the blink of an eye with almost same accuracy as that of a human eye. It is not just about converting a picture into pixels, and then try to make sense of what’s in the picture through those pixels, you will have to first understand the bigger picture of how to extract information from those pixels and understand what they represent.

## How do machines see? Let's Dive in!

- **CS Legacy. Represent Colors by number:** In computer science, each color is represented by a specified HEX value. That is how machines are programmed to understand what colors the image pixels are made up. Whereas as humans we have an inherited knowledge to differ between the shades.
<figure>
  <img src="https://raw.githubusercontent.com/akhilesh-k/blogs/master/images/cv2.gif">

 </figure>

- **Image Segmentation:** Computers are made to identify similar group of colors and then segment the image i.e. distinguish the foreground from background. The technique of color gradient is used to find edges of different objects.
<figure>
  <img src="https://raw.githubusercontent.com/akhilesh-k/blogs/master/images/cv3.jpg">
    <figcaption>Pixels are multiplied together for the comman areas of color.</figcaption>
 </figure>
- **Finding corners:** After segmentation, images are then looked up for certain features, also known as corners. In simple words, algorithms search for lines that meet at an angle and cover a specific part of the image with one color shade. Features, also called corners are the building blocks which help to find more detailed information contained in the image.

- **Find textures:** Another important aspect to identify any image correctly is to determine the texture in the image. The difference in textures between two objects makes it easier for a machine to correctly categorize an object.

- **Make a guess:** After implementing the above steps, a machine needs to make a nearly-right guess and match the image with those present in the database.
<figure>
  <img src="https://raw.githubusercontent.com/akhilesh-k/blogs/master/images/cv5.png">
  <figcaption>The calculation of Curvature of Road is the predictive model.</figcaption>
 </figure>
- **Finally:** See the bigger picture! At last, a machine sees the bigger and clear picture and checks if it was right identifying the one, as per the feeded algorithmic instructions. The accuracy has improved a lot in past years but still, machines make mistakes when asked to handle images with mixed objects.

## Prerequisites.

**Beginner level**

A. Mathematics :

1. Linear Algebra
2. Singular Value Decomposition
3. Introductory level Pattern Recognition
4. Principal Component Analysis
5. Kalman filtering
6. Fourier Transform
7. Wavelets

B. Image Processing:

1. Online Course offered by Duke University on Coursera
2. Digital Image Processing by Gonzalez and Woods

**Advanced level**
1. Linear Discriminant Analysis
2. Probability, Bayes rule, Maximum Likelihood, MAP
3. Mixtures and Expectation-Maximization Algorithm
4. Introductory level Statistical Learning
5. Support Vector Machines
6. Genetic Algorithms
7. Hidden Markov Models
8. Bayesian Networks

**Theoretical Parts are alright, Now when we have to implement we have to move to softwares frameworks and tools**

1. Octave / MATLAB
2. OpenCV (C++/Python)

There are some awesome moocs which are available freely on Internet:
1. [Udacity : Introduction to Computer Vision](https://www.udacity.com/course/introduction-to-computer-vision--ud810)
2. [Stanford’s CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu) Visit there Youtube Channel for Videos.

---
Check Awesome Computer Vision [Repository](https://github.com/jbhuang0604/awesome-computer-vision) which has more resources.