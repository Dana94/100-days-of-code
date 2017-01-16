### Day 15: January 15, 2017
##### flower-slideshow

**Today's Progress**: Thanks to Bootstrap, I finally centered the main image. Now I'm configuring a button to change the gallery from grid to column format. The grid would show the images smaller but more to see in one view. The column would show them bigger, not all seen at once, and it would take up less room on the screen. The gallery images are filled using a function rather than directly into the html.

**Thoughts:** Every time I finish one part in this program, I suddenly come up with another function to try and implement. It's a good feeling. : )

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/f589e5bcaa081f31a0de273db2f67bc977480e92)

### Day 16: January 16, 2017
##### flower-slideshow

**Today's Progress**: I now have the gallery layout button able to change the column width of the gallery and the frame containing the main image whenever the user wants to see their images in another type of display.

**Thoughts:** I'm having trouble filling the images into the grid layout of the gallery. There seems to be more padding for some reason so they're farther apart then I'd like to see. I also learned something today. Apparently adding the start of a div to the inner html will have the closing div added for you.  For example, after container.innerhtml = <div..>, the closing div will automatically be placed after it so you don't have to. I find this odd because if I am looping through images and plan to add a closing div after it. It could change the column width of the elements. I found this out by doing cosole.log when trying to figure out why my images were not positioning in the way I expected.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/932347a287eeb69c92c0474f8f5b5995d9cb8917)
