# 100 Days Of Code - Log

### Day 0: December 30, 2016 
##### color-buttons program

**Today's Progress**: Clicking a button changes the background color of it. The color will be chosen by random RGB values. 

**Thoughts:** I wanted to do something that seemed pretty simple in my head, but I wanted to test myself to see how much of a struggle it would be. I was having some trouble in the end with setting the RGB values in the jQuery .css() method. It turns out I forgot the commas. :)

**Link to work:** [color-buttons](https://github.com/Dana94/color-buttons/commit/091344822867a2671bf70d323a81d2fd4252c1bd)

### Day 1: December 31, 2016 (Happy New Years!)
##### flip-book program

**Today's Progress**: I created a button that changes the image currently shown. Clicking it repeatedly will show a figure doing a jumping jack. Currently working on the other part of the program. It will have the user click on a button and the image will run as a flip book impression. The figure will appear to be jumping up and down until the button is pressed again.  

**Thoughts:** I am experimenting with event handlers since I know there is more than one way to use them. I need to fix the function for the start/stop button because there must be an easier way to identify what image is currently displayed in order to replace it with the other one. Maybe just put the values in an array to save typing them out? We'll see. I need to lengthen the time lapse between switching out the picture for the second button's function, else the user won't be able to see the figure doing the jumping jack. 

**Link to work:** [flip-book](https://github.com/Dana94/flip-book/commit/2467ab3a431b4e4121a2fb7dfd51a73aa5966079)

### Day 2: January 1, 2017
##### flip-book program

**Today's Progress**: Now the second figure will continually jump up and down once the start button is clicked. The stop button will stop the program. I also put the string values of the image tags into an array to avoid having to write them out each time they're needed. 

**Thoughts:** I used the time interval functions today. I want to try and make one button that can start and stop the program as the images switch during the time interval. I'm still trying to figure out how with the event handlers, I keep cancelling the other one out.

**Link to work:** [flip-book](https://github.com/Dana94/flip-book/commit/5120f34c5655b6786e57cf0ad8b78c8fd0417df7)

### Day 3: January 2, 2017
##### flip-book program and flower-slideshow

**Today's Progress**: Now the second figure will start and stop with one button being used. I have moved onto another program which is a simple gallery that can shift between images. Right now I'm trying to resize the images so they fit in the center of the page.

**Thoughts:** I realized that in order to have the same button stop the timer, I needed to remove the event listener that started it in the first place. I thought that just adding a new event listener would override the other, but I was wrong.

**Link to work:** [flip-book](https://github.com/Dana94/flip-book/commit/9d9c364f3e508f58d1c91e1cf75bb0f57738f3b2), 
[flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/b02fdc0f4a045f3d98e26a73aa0e448c04ec71a9)

### Day 4: January 3, 2017
##### flower-slideshow

**Today's Progress**: The buttons will shift through the images in the gallery in the direction the user chooses.

**Thoughts:** I'm trying to resize the images so whether or not one of the images is big, it would still fit in the center of the page. I'm considering to have a time interval put in so the images will continue to show without the buttons being clicked.

**Link to work:**[flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/77f7e0b8c2d5bf0f8882fd2644c034ac4ddb410c)

### Day 5: January 4, 2017
##### flower-slideshow

**Today's Progress**: Using jQuery to have the images fade out and fade in to the next one.

**Thoughts:** It turns out "slow" for fadeOut is not as slow as what I'm looking for so I'm trying to find the right speed to have a noticable gap of time between each image that is displayed. What I am trying to figure out is how to insert the next image in by the time it will fade back into view.

**Link to work:**[flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/661f2e68f95118bb70b1b89fb4da29534234deaa)
