+++
title="Making the lectures"
+++

These are instructions for making lectures similar to [file:///home/gadgil/lectures/lecture1.html#/](file:///home/gadgil/lectures/lecture1.html#/). The technical expertise needed is roughly the same as making a personal web page (with HTML).

#### Download and test

1. Download the [zipped folder](http://math.iisc.ac.in/~gadgil/lectures.zip) or the full [google drive folder](https://drive.google.com/drive/folders/1McWVgZZL_422I51EY_pAeZGsbdW_Acuw?usp=sharing).
2. Unzip if it is downloaded as a zipped file.
3. Open the file `lecture1.html` in your browser; double-clicking on this file should do this.
4. Edit the file `lecture1.html` or make copies and edit to make our own lectures.

Some details on making lectures are below.

#### Slide-shows (lectures)

The slide shows are made with [reveal.js](https://revealjs.com/), whose documentation gives details and demos of the many nice things we can do with it. 
For a minimal setup, however, all you need to do is (copy and) edit an HTML file which has all the required configurations in it, such as the `lecture1.html` 
(which in turn was made by editing a file included with `reveal.js`)

#### Videos

The videos are embedded from YouTube (to which I uploaded the videos after making them). Clicking on _share_ in YouTube gives the option of embedding a video.
The only change I have made manually is the size of the frame (as the default is a bit small for lectures). An example of embedding is below, where only the `width` and `height` have been changed from the code provided by YouTube.

```html
<iframe width="853" height="505"  data-src="https://www.youtube.com/embed/hFtqRCmM6ys" frameborder="0"
    allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen></iframe>
```

The videos were made on an Ubuntu linux system using a Wacom tablet, Xournal++ (as the whiteboard) and Kazam (for recording screens), but this is one of many possible setups.

#### Quizzes

The quizzes are made using __Google Forms__, which has quizzes as an option, including (limited) auto-grading. It is best to make them with a _G Suite_ account, so that during the course they can only be answered by those from within IISc (or equivalent).
