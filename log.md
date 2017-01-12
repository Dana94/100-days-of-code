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

**Link to work:** [flip-book] (https://github.com/Dana94/flip-book/commit/5120f34c5655b6786e57cf0ad8b78c8fd0417df7)

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

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/77f7e0b8c2d5bf0f8882fd2644c034ac4ddb410c)

### Day 5: January 4, 2017
##### flower-slideshow

**Today's Progress**: Using jQuery to have the images fade out and fade in to the next one.

**Thoughts:** It turns out "slow" for fadeOut is not as slow as what I'm looking for so I'm trying to find the right speed to have a noticable gap of time between each image that is displayed. What I am trying to figure out is how to insert the next image in by the time it will fade back into view.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/661f2e68f95118bb70b1b89fb4da29534234deaa)

### Day 6: January 5, 2017
##### flower-slideshow

**Today's Progress**: I successfully got the images to fade out and change to the next one in the list before fading back in.

**Thoughts:** So I realized that it made more sense to hide the div that contained the flower image since it would fade out the div and its contents with it. By doing that, I could change the image in the div and still have it not show until the div itself faded back into view.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/a51392638fbaa9b053558629040f5eac8802f0fd)

### Day 7: January 6, 2017
##### flower-slideshow

**Today's Progress**: I added a timer interval to have the images continue to display without a user clicking the buttons.

**Thoughts:** I thought I had to clear the timer whenever the buttons are clicked, but I don't think that's the case. I made the interval about 5 sec long between each image, but may lengthen it so the user has time to click the button.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/4ce0c2384d65a1daddcb2d1c2ad9ca2e8d4593a1)

### Day 8: January 7, 2017
##### flower-slideshow

**Today's Progress**: I'm working on displaying the images in a row below the large one shown above them.

**Thoughts:** I'm having difficulty changing proportions of the yellow rose. It is the only image in portrait form. I looked up some info regarding this image sizing issue. It seems that if it is a landscape image in a portrait container, then do width: 100% for the image. If it's a portrait image in a landscape container, then do height: 100% for the image. I'm still testing this out.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/bb882b8de6ad20ef259a00c3e9a84b6622579081)

### Day 9: January 8, 2017
##### flower-slideshow

**Today's Progress**: Resizing main image so the dimensions can be used on all landscape and portrait images.

**Thoughts:** So I used transfom: scale() on the main image, which would fit in the yellow rose. But I had to add many padding and margin values to accomodate its height. Now the landscape images are much higher up when displayed. I'm sure I'm missing an attribute or something that can fix this better than what I'm trying to come up with. The more css I add to the objects, the more I believe that the view of the slideshow will vary greatly on another screen.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/61e76614542ede1b65d08b38a13506461d5db0bd)

### Day 10: January 9, 2017
##### flower-slideshow

**Today's Progress**: Trying to construct a tool that will automatically resize the images correctly by checking its height and width.

**Thoughts:** For once, the yellow rose image seems to have almost centered properly in the page. But the margin-top or padding-top could be adjusted to make sure the smaller images will not move up and down between each big image being displayed.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/f87092ec943b68efe5ad9541635dd14890a54e25)

### Day 11: January 10, 2017
##### flower-slideshow

**Today's Progress**: Moving away from repositioning the smaller images. Now I'm trying to have the correct dimensions of the next image read before it can be diplayed.

**Thoughts:** I want this program to be ready for more than 10 images in its slideshow, so I decided to change the format again. I'm working on having the program read the height and width of the next image because now it only reads the previous one.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/694743be1988e40ccf6c8b384a0c44e73533fb1d)

### Day 12: January 11, 2017
##### flower-slideshow

**Today's Progress**: It doesn't look like much of a difference, but I made the images bigger and centered them.

**Thoughts:** Resizing and repositioning the images over and over again can get tiring fast. I'm proud for figuring out the fade-out-in for the images, but when it comes to presentation on the whole page in general, I would like to see this as a 'classy' looking slideshow. Still defining what 'classy' entails...

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/3185680cf8ede2371d171c05c74f3c528c7f5e27)

### Day 13: January 12, 2017
##### flower-slideshow

**Today's Progress**: I decided to take a different approach and focus on the design of the whole thing. The images in the gallery will appear on the left while the one in focus will show on the right.

**Thoughts:** I'm working on how to keep the window from growing once more small images appear on the left side. I decided to ask my question on the FreeCodeCamp forum. I'm not against asking for help, but I always worry that I'll receive less "here's the solution to your problem..." and more "this is what you should do instead of your idea...". Until then, I'll be looking around more for a solution.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/61e7011d8b03826b8546bb6ff64522cf9611651f)
