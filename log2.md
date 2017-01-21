### Day 15: January 15, 2017
##### flower-slideshow

**Today's Progress**: Thanks to Bootstrap, I finally centered the main image. Now I'm configuring a button to change the gallery from grid to column format. The grid would show the images smaller but more to see in one view. The column would show them bigger, not all seen at once, and it would take up less room on the screen. The gallery images are filled using a function rather than directly into the html.

**Thoughts:** Every time I finish one part in this program, I suddenly come up with another function to try and implement. It's a good feeling. : )

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/f589e5bcaa081f31a0de273db2f67bc977480e92)

### Day 16: January 16, 2017
##### flower-slideshow

**Today's Progress**: I now have the gallery layout button able to change the column width of the gallery and the frame containing the main image whenever the user wants to see their images in another type of display.

**Thoughts:** I'm having trouble filling the images into the grid layout of the gallery. There seems to be more padding for some reason so they're farther apart then I'd like to see. I also learned something today. Apparently adding the start of a div to the inner html will have the closing div added for you. I find this odd because if I am looping through images and plan to add a closing div after it, it could change the column width of the elements. I found this out by doing console.log when trying to figure out why my images were not positioning in the way I expected.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/932347a287eeb69c92c0474f8f5b5995d9cb8917)

### Day 17: January 17, 2017
##### flower-slideshow

**Today's Progress**: I am working on a function to fill the gallery for the grid layout. I need to have a new div row added after every 4 images are displayed. Whenever I try to add another row to the inner html of the gallery it doesn't work. So the first row gets filled with 4 images, but then the program has trouble.

**Thoughts:** I was looking into creating a div element and then appending it to the gallery, but then it involves nodes and I'm not sure if this is the right solution to this problem. I don't see why it is so difficult to just add another gallery row so the next 4 images could be put in it.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/37f0152c22b0163bbf8ecfd33c11c6058899647a)

### Day 18: January 18, 2017
##### flower-slideshow

**Today's Progress**: The button that changes the gallery to column and grid format not only changes its width, but now fills the images in a certain format. The column will have the images filled within one 'row' and the grid will have 4 images maximum on each row. The column is meant to see all the images in a larger size, while the grid is more of a condensed total of all the images.

**Thoughts:** Instead of adding html bit by bit into the index.html file, I decided to concatenate a string (called html) that will insert its contents through jQuery once all the images are looped through. I am really glad this is working. Now I am looking into having each image clickable so a user can choose an image and have it displayed immediately. I'm not sure if the slideshow will continue from the chosen image or it will continue where it left off before a user chose an image to see.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/a024acf10a90218ea2dc39d3914bb9633f47360e)

### Day 19: January 19, 2017
##### flower-slideshow

**Today's Progress**: The buttons now have symbols instead of words. I may use glyphs of arrows from Bootstrap for the direction buttons so they are all the same style. I also added a new image and now if you click on any small image, it will appear on the right side in a larger size. Once the user's chosen image is displayed, the slideshow will continue from where it left off.

**Thoughts:** I really like how this program is turning out. I never had a design in mind when I first started working on this, but later on I just started brainstorming ideas from other galleries I've seen and knew I wanted to design a responsive one like theirs.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/15d105cc86a23d412684d799354db80aefb85461)

### Day 20: January 20, 2017
##### random-quote-machine, danaottaviani.github.io

**Today's Progress**: I had limited time today, so I removed some tech experience on my resume site to highlight my flower-slideshow, and started working on my random quote program.

**Thoughts:** Not much to say today. I want to have a simple and focused design for the random quote program, maybe have the text show in fancy cursive or something.

**Link to work:** [random-quote-machine](https://github.com/Dana94/random-quote-machine/commit/4629b6b3736068c11f38c161c98f67d409b00e0e), [danaottaviani.github.io](https://github.com/Dana94/danaottaviani.github.io/commit/391d03f43e1910afd0e592ceb8dda4421a860a2d)

### Day 21: January 21, 2017
##### flower-slideshow

**Today's Progress**: I am working on a button for uploading images into the gallery. I guess they will be added to the array, which means some things in the app.js file need to be altered. I can't expect all images uploaded to follow the 'name-rose.jpg' format.

**Thoughts:** I had a hard time finding any instructions on developer.modzilla.org on implementing an upload tool in my program. I found the input tag as an option but not sure on how to make it work through my own button.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/7c2741e8c2008b0c8e719020aec3f92142f8c18d)
