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

### Day 22: January 22, 2017
##### flower-slideshow, calculator

**Today's Progress**: I submitted another question to the Free Code Camp forum on my uploading function in the flower-slideshow. I have never done this before and I don't want to google some quick solution, though I am not finding anything else to guide me here. I also went back to the calculator program. It has been a while and it looks pretty depressing. I just changed the button style and aded event listeners so the name of each button is the value that appears in the text box. I really want to create a nice sleek design for this program. Once I create a basic calculator, I'd like to find a way to incorporate my math knowledge to create a more complex device, like a graphing calculator.

**Thoughts:** I need to get back on the programming bandwagon. The more questions I ask and the more time I invest will no doubt improve the knowledge I currently have.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/7e4cbad91ca68517d667073d54af87028e9063e4), [calculator](https://github.com/Dana94/calculator/commit/37b9babefedb19918115e219b58577af2642d5a0)

### Day 23: January 23, 2017
##### random-quote-machine

**Today's Progress**: I would like to expand this project into a quiz to see if a user could guess which person said the quote. Since I would like to continue forward in Free Code Camp, I will submit what I have once the randomization is finished and change it later on.

**Thoughts:** I added a progress bar so the user could visualize how many quotes they haven't seen yet. It works so far, but I have to get a new index value if the one chosen already contains the value 'true' for its 'shown' property.

**Link to work:** [random-quote-machine](https://github.com/Dana94/random-quote-machine/commit/14bb7c3ace1845e1aa49e95cbdd2f0339072e923)

### Day 24: January 24, 2017
##### random-quote-machine

**Today's Progress**: I am nearly done with having this program work with a randomization function. Right now I am trying to have a reset button start the progress bar from 0 and have all the quotes redisplayed randomly again.

**Thoughts:** As I am typing this, I realize the reset button won't work until all the 'shown' values are changed to 'false' again. That could be what is keeping the reset button from working.

**Link to work:** [random-quote-machine](https://github.com/Dana94/random-quote-machine/commit/01226de4a6f9cb9e24af53182580d410ec126669)

### Day 25: January 25, 2017
##### random-quote-machine

**Today's Progress**: So the reset button works and a user can keep pressing the buttons to have the list of quotes display from the start to end in a random order. I also added a Twitter button, the symbol was found on fontawesome.io. 

**Thoughts:** I completely forgot the user story about having the ability to tweet the quotes. I have no experience in this so if I need to have a Twitter account for this to work, then I am out of luck. I don't have one :). Maybe I can do email if that is the case.

**Link to work:** [random-quote-machine](https://github.com/Dana94/random-quote-machine/commit/05813ff9c8fea055ba6616057a7eede714ea8c96)

### Day 26: January 26, 2017
##### random-quote-machine

**Today's Progress**: I believe I properly added the Twitter button's functionality so a user can tweet any of the quotes.

**Thoughts:** I have the code in CodePen.io so someone in the forum could look at it and let me know if something is not working for them. I want someone's opinion before submitting it.

**Link to work:** [random-quote-machine](https://github.com/Dana94/random-quote-machine/commit/b4180fbe36d8a6e5741704fc58e7ebf3264104cd)

### Day 27: January 27, 2017
##### flower-slideshow

**Today's Progress**: I'm sorry to report I did far more reading up articles on the best steps to take to implementing the upload feature than on coding it. I'm trying to avoid reading a tutorial on how this process is done and using their code to make it happen (with their ownership mentioned of course), but I think this is the best way to be honest. I have never done this before and I have no idea what I am doing right now.

**Thoughts:** I had to fix the Twitter button but now I have a post requesting feedback for my random quote machine. Hopefully good feedback is returned.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/cd608311a7a1a9c014ba1704fe3685d470ed5bd9)

### Day 28: January 28, 2017
##### random-quote-machine

**Today's Progress**: Some feedback received was that the layout was messing up in different screen sizes and that I ended up concatenating each quote together whenever the Twitter button was pushed. I fixed those issues, I still want to test out the layout more before submitting it.

**Thoughts:** I find that I am constantly reminded {display: block, margin-right: auto, margin-left: auto } could help center objects. I guess Bootstrap can't do everything.

**Link to work:** [random-quote-machine](https://github.com/Dana94/random-quote-machine/commit/e37a421ad5aaecf20b270743da313e4bea9ab613)

### Day 29: January 29, 2017
##### flower-slideshow

**Today's Progress**: The layout looks really bad in mobile so that's what I've been working on today. It doesn't look any better yet.

**Thoughts:** I am trying to change the button sizes when the screen width decreases. Also, the width and height of the whole page does not seem to fix to the mobile screen. You can still move the page around and see white space off to the right and the bottom. I though height: 100% and width: 100% would help but I don't think I'm doing it right.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/4635174f463f138d0cbaa046281e938039bcacc4)

### Day 30: January 30, 2017
##### random-quote-machine

**Today's Progress**: After playing around with the screen sizes, I think the layout now looks good on mobile devices.

**Thoughts:** Hopefully the sucess in improving the layout in this program can help me finally make the flower-slideshow program look decent in mobile devices too. I worked on it today but it doesn't look like much has changed.

**Link to work:** [random-quote-machine](https://github.com/Dana94/random-quote-machine/commit/02bfc86e9a46db84c4efd14fdd5c15d34da2d31d)

### Day 31: February 2, 2017
##### flower-slideshow

**Today's Progress**: Okay, so the mobile view is starting to improve, but now it seems the buttons' spacing needs to be altered. I'm guessing playing around with the grid columns should help.

**Thoughts:** This program is starting to look pretty nice! After the display is FINALLY finished, I want to go back to the upload feature. It should be my last thing to do.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/7cb4b3daa88119d6a7b5d90f3ace06a31c460f93)

### Day 32: February 3, 2017
##### flower-slideshow

**Today's Progress**: The layout still isn't better in mobile, BUT the buttons are going to have more room on the top once I cancel the option to have a mobile user choose grid form for the photos. It wouldn't make sense to have another display for the images that would take up more room on the screen.

**Thoughts:** Not many thoughts today, I think other people have the same trouble with CSS as I do, I only hope something will finally click and everything will be laid out like I want it to be.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/8d2a920368a21401f430d1afc4590f7c1a9215b4)

### Day 33: February 4, 2017
##### flower-slideshow

**Today's Progress**: I have made progress today! When the program is viewed in a phone screen size, the gallery-layout button is removed so the grid format won't take up more of the small screen. Also, I think the buttons are a good size when their font is enlarged so they are easier to read.

**Thoughts:** I just need to do a few more tests to make sure the buttons look good on all screen sizes, then I can go back to working on the upload feature. I'll be relieved once I'm past this styling business.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/420efcd39a9f85952284e5910a6972e1e4c33ea9)
