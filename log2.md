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

### Day 34: February 6, 2017
##### flower-slideshow

**Today's Progress**: I did multiple tests with Google Chrome's mobile devices to see how the buttons would look in different screen widths. It looks like everything is good and now I will continue to work on the upload feature for one of the buttons.

**Thoughts:** Not much to say, I'm just glad the buttons are done styling. I hope succeeding in the upload function will help me understand how the export feature works if I ever need to use it, perhaps on my own site.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/4825b668ddf40392f942d26a8b73c1783afc61cc)

### Day 35: February 9, 2017
##### weather-app

**Today's Progress**: I am trying to keep up with Free Code Camp projects, so I started a weather-app that will show a user their location's current temperature and weather.

**Thoughts:** Since this project will require a weather API, I can start getting the hang of using these kinds of tools for future projects.

**Link to work:** [weather-app](https://github.com/Dana94/weather-app/commit/8e7037dfa2e9c88c8feb4401f49bd6ff50a36583)

### Day 36: February 10, 2017
##### weather-app

**Today's Progress**: Thanks to css-tricks.com, the images now show up perfectly on all devices. I've been looking at the weather API mentioned on Free Code Camp, but I am planning to try and use a jQuery plug-in instead so I won't have to use an API key.

**Thoughts:** I really like the design so far, a beautiful background pic expressing the current weather with a semi-transparent middle column displaying the information. 

**Link to work:** [weather-app](https://github.com/Dana94/weather-app/commit/e3796480026ee3318755900697504287d264cbd2)

### Day 37: February 11, 2017
##### weather-app

**Today's Progress**: Nothing new, except I decided to use different weather fonts from fontawesome.io to show a symbol for the weather aside from writing it out.

**Thoughts:** I bookmarked a bunch of posts related to AJAX and other people's questions regarding this project on Free Code Camp. I plan to read them to see why I am having difficulty in retrieving the correct info when using lattitude and longitude obtained from geolocation.  

**Link to work:** [weather-app](https://github.com/Dana94/weather-app/commit/32b65c7ab95c1afaf4a8e5bc34e0c0ca8ae16fcd)

### Day 38: February 12, 2017
##### weather-app

**Today's Progress**: Got the weather coming in through simpleweather.js! I had to download the zip file because the script for the link didn't seem to work. I'm now trying to understand what command retrieves what and how I can use the info to personalize the page according to the user's location.

**Thoughts:** I am now trying to figure out a simple way to know what key words like 'snow' and 'cloudy' can be read and implemented in the icons and backgound picture. Since weathers can happen at once like 'snow and rain', I need to decide what takes precedence since there can only be one background picture that describes the weather.

**Link to work:** [weather-app](https://github.com/Dana94/weather-app/commit/b8067bd112f310016382321c8d4d6cf4d2b96c31)

### Day 39: February 13, 2017
##### weather-app

**Today's Progress**: I added more images and started analyzing the condition text to see how I can pull the best background image to represent the weather.

**Thoughts:** I am trying to sort the weather words so 'snow' will come before 'cloudy', while 'windy' weather can just show a day or night image. I think I can also see what time a location experiences the sunrise and sunset and can put in an image with the sun rising or setting to match it.

**Link to work:** [weather-app](https://github.com/Dana94/weather-app/commit/b0dd2c2de48ec08cd0b06b118bb8b89d540a56e2)

### Day 40: February 15, 2017
##### weather-app

**Today's Progress**: I decided to add the weather info to an object called 'myWeather' so I can use it in other parts of the program. I find it easier than having everything done in the simplyWeather function that receives the info. I also reversed the array to show precedence between the weather conditions. The last word found in the myWeather.condition string should be the weather displayed in the icons and background.

**Thoughts:** I want to use thermometer icons so I need to create a range that would make the displayed thermometer icon (half, full, empty) resemble the current temperature.

**Link to work:** [weather-app](https://github.com/Dana94/weather-app/commit/eb81d67d2f8a35bb4122db3ce3112c2640f4d792)

### Day 41: February 18, 2017
##### weather-app

**Today's Progress**: I have a thermometer representing the fahrenheit temperature. I'll probably change it to a switch statement later. I'm also getting familiar with the Date object. I want to change the background to a sunrise or sunset image if the current time is within 20 min before their sunrise/sunset time and 20 min after their sunrise/sunset time. I chose 20 min because that seemed like a reasonable amount of time, may change it later.

**Thoughts:** I'm tryng to personalize this enough so it really represents the user's current weather. I'm not really sure what all my plans will be, but I'm willing to experiment with the info the plug-in gives me.

**Link to work:** [weather-app](https://github.com/Dana94/weather-app/commit/8fbb592484deb5c12247ec1c734056fa0fe3e3a3)

### Day 42: February 19, 2017
##### weather-app

**Today's Progress**: Just worked on more conditionals for deciding which icons to display. I'm still struggling with the sunset/sunrise times. I know they are in string format for easier use, but I want to use them to check if the user's current time is close enough to those times in order to put a sunrise/sunset image in the background. I looked on Stack Overflow for this and found some stuff I'll try to implement tomorrow.

**Thoughts:** Nothing much, still dealing with the string times.

**Link to work:** [weather-app](https://github.com/Dana94/weather-app/commit/fadec6f8da6ff29fa175be9eb887d90b0a19f24c)

### Day 43: February 20, 2017
##### weather-app

**Today's Progress**: I added 20 min to the current time and subtracted 20 min to check that the minus 20 min is before the sunrise/sunset time (individually) as well as the plus 20 min is after the sunrise/sunset time. This will give a fair interval to still show the background image that best represents the sky.

**Thoughts:** I'm going to look up more images that will add more weather condition options for the background.

**Link to work:** [weather-app](https://github.com/Dana94/weather-app/commit/e39b076b722e0d1c7cbbff9e8577776bfd446cc3)

### Day 44: February 21, 2017
##### weather-app

**Today's Progress**: I didn't do anything new today except check the screen sizes (which need a bit more tweaking) and to decide of there will be anymore plans for this app. Maybe some small animation will give it more of a unique design.

**Thoughts:** I want to put the project on Code Pen for review before submitting. I want to have other people's opinions about the design. Is it too simple? Or is it better this way?

**Link to work:** [weather-app](https://github.com/Dana94/weather-app/commit/4439f2ea6fea65bae5d7823f16c2e63a4b15fbd9)

### Day 45: February 24, 2017
##### weather-app

**Today's Progress**: I just cleaned up the code and spent a good 20 min trying to put the code on Code Pen :P. I knew that GitHub could put the site live, but thought I could only do a limited number of projects, good thing I was wrong. Much easier to link to the live site then do all the copy-and-pasting to Code Pen. I asked for a review on Free Code Camp. https://dana94.github.io/weather-app/

**Thoughts:** I have other visual projects I want to work on. But at the same time I want to get into Sass and other code like CSS that I have never used before. I'm looking forward to this expanding my skills compared to what I know now in terms of visual and user-friendly design.

**Link to work:** [weather-app](https://github.com/Dana94/weather-app/commit/f2630f4185fd0f56c45a795f82b590f365668e62)

### Day 46: March 1, 2017
##### clock

**Today's Progress**: It's been a few days. I've been swamped with homework and tests. I came up with a new program which is an analog clock. It will show the hour, min, and sec hand representing the real time. For today, I just added the color scheme.

**Thoughts:** I've been learning SASS on Codecademy, but I thought I should continue with a new project to keep up with the 100 days of code plan.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/995ae02bc5d54b98f81b595f3c602ff4da874a11)

### Day 47: March 3, 2017
##### clock

**Today's Progress**: Managed to get the min hand to pivot around the center. I want to fix the padding-top and left so it will look good on mobile too.

**Thoughts:** I'm excited to see this when it's complete!

**Link to work:** [clock](https://github.com/Dana94/clock/commit/15adeb8bd88a868e291139aaa7b9a10385e82dd3)

### Day 48: March 5, 2017
##### clock

**Today's Progress**: I added the second hand and I think they look pretty centered. I had to change the transform-origin values so their top left corners wouldn't move from its point when the divs rotated. Then I had to overlap them with z-index do they'd all stay in the center of the clock.

**Thoughts:** I'm probably going to work on having one hand reflect the current time at first so I know that I'm doing it right. Probably the second hand since its position is constantly changing. Not sure if I should add some numbers or something on the face.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/1a44c055eaa45f2746f460a74ea63470264e0df0)

### Day 49: March 6, 2017
##### weather-app

**Today's Progress**: I realized that the currentPlus20/Minus20 times were not being compared properly with the sunrise/sunset times. I think I fixed it, will have to wait until later :).

**Thoughts:** I'm glad that seemed like an easy fix with a little trial-and-error. Thank goodness for console.log.

**Link to work:** [weather-app](https://github.com/Dana94/weather-app/commit/4bcdcab403ae025e8019237c0258305a8326fabe)

### Day 50: March 10, 2017
##### clock

**Today's Progress**: So the weather-app seems done (again) so now I am back to the clock program. I decided to try and add small tick marks along the clock face to show the numbers. I never understood how precisely someone could read a clock with no representation of numbers on it :/.

**Thoughts:** I thought I finally got the '12' tick in its right place, but it seems to alter the origin of the hands when I minimize the screen. I need to work on this.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/d9382cd59f0828b2bddb0c729f657e30d2bcd555)

### Day 51: March 12, 2017
##### clock

**Today's Progress**: I took a break from trying to make the ticks work with the hands, but I did successfully make the hands represent real time.

**Thoughts:** I plan to work on displaying the numbers next time. I just don't want to mess up the hands since they are working now.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/ea47de4cd0ce6238791a43d71a2409980d402671)

### Day 52: March 13, 2017
##### clock

**Today's Progress**: I added the ticks for the 12,3,6,9 on the clock. I think they are evenly positioned. I want the hands to completely cover the ticks when they land on it.

**Thoughts:** Working on 1 and 2 now. They need to be rotated more and I wonder if I can try to get the witdth and height of the clock to make their position more accurate. I'm just doing this by eye now.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/89bcdd3731da38af7fe07460ba7eadc1c1990f3f)

### Day 53: March 14, 2017
##### clock

**Today's Progress**: All the 'numbers' are on the face now. I want to check if the hands fall evenly on each one, but I won't sweat too much of the small stuff.

**Thoughts:** When I have this clock done, I can easily customize the face to be something else, like a character from pop-culture :).

**Link to work:** [clock](https://github.com/Dana94/clock/commit/c2a4a118fc509b6c7a3df74707291fc639a4cd2a)

### Day 54: March 17, 2017
##### clock

**Today's Progress**: New clock face in the making! I'm using shapes to construct the face for this pop-culture icon. ;)

**Thoughts:** The more CSS I write, the more I think I should transfer this code into Sass. I took a course on Codecademy on it and it would definitely solve the lengthy problem I have now. Will look into this later in the week.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/f19c37828a5b03abab6d5786e809f3a7340570b0)

### Day 55: March 18, 2017
##### clock

**Today's Progress**: I added the hands and fixed the z-indexes so the correct parts will overlap. I'm working on the accessory now and I need to use separate shapes to make it. It's harder than it looks.

**Thoughts:** Haven't gone into Sass yet, but I will soon! I'm just trying to make this second clock face as close to the character as I can.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/6e84ebe2dd8449dcf99a44d244263cb7dbe303da)

### Day 56: March 20, 2017
##### clock

**Today's Progress**: So the bow is done (I think) and now onto the whiskers. They look kind of weird and I'm not sure if I'll keep them yet. :/

**Thoughts:** Ugh, the CSS length is killing me! I put a table of contents in the beginning. Someone gave me that tip once.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/fb5f36f1c4995f6b1ab25a74df92f5f655309de4)

### Day 57: March 22, 2017
##### clock

**Today's Progress**: Added the right-side whiskers. I spent a lot of time with the sass file. I think I'd prefer scss for this one though, I learned about it on Codecademy.

**Thoughts:** It just doesn't seem that the scss code is "correct" in the file. I thought it would have the same color-coded words like CSS does. Maybe something was written wrong, I'll see to this next time.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/73191b97f486638f719b9dd544dee924ce2f1dff)

### Day 58: March 23, 2017
##### clock

**Today's Progress**: Removed the scss file. I thought that from now on I'll just start with sass or scss and update a css file along side it. There is really no use to putting one in this program.

**Thoughts:** I need to work on the extra spacing in the mobile view (which seems like a neverending issue with my projects). Then I want to look at the hands again to be sure they are straight.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/57d07f1a8fce31f585da4f2951bfcfe4548616ee)

### Day 59: March 24, 2017
##### clock

**Today's Progress**: I am still testing to see if the column structures will help balance out the kitty clock features.

**Thoughts:** I made the program public and asked Free Code Camp forum for advice on the column/margin/padding issue I have now.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/f3e0c0d2bbfac0b2c465e17c139acc606e9de2e2)

### Day 60: March 26, 2017
##### clock

**Today's Progress**: I received some feedback from the forum. It would be better for me to rely more on margin/padding and the top/bottom/right/left commands for nested divs rather than the columns. I guess this makes it easier. I wasn't sure about the columns working for me anyway. I am still straightening out the ticks on the first clock face and then want to tackle the extra space in mobile.

**Thoughts:** Nothing much to say, I'm still fixing small details since I don't know what my next step is for this project. I may move onto something else soon when I am ready.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/d422fcc1668064638c01f5042c57804df4ee9375)

### Day 61: March 31, 2017
##### clock

**Today's Progress**: Fixed the mysterious extra margin in mobile. I believe the black trapezoid caused the extra space due to its large margin value. Glad that is over. I'm using [screenfly](http://quirktools.com/screenfly/) to test the current program as I'm working on customizing the view and sizing in different mobiles.

**Thoughts:** I won't be done with this until it is mobile ready, then, I don't know, maybe finally work on a portfolio site? I finally have some of my own creations to show there. :)

**Link to work:** [clock](https://github.com/Dana94/clock/commit/3c1c18e51ebc1529e254237a726adbbe9cc8eac7)

### Day 62: April 2, 2017
##### clock

**Today's Progress**: The clocks show nicely on phone screens. Onto tablets!

**Thoughts:** I am going to have sooo many media queries when I am done with this program. I'm not sure if I want to display the clocks at the same time, or maybe have the user choose their preference.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/f8a84f655152c7768813fb9e9be1808195fe499f)

### Day 63: May 9, 2017
##### clock

**Today's Progress**: Thanks to screenfly, it seems that my work with phones is not done. Will continue to check that all sizes look good.

**Thoughts:** I mentioned in my previous post on whether the user should decide on what clock they want to show. It may make things easier for me since only one clock will be displayed.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/e53bd534c7379f2b36fe4849b02e2b64873557e6)

### Day 64: May 10, 2017
##### clock

**Today's Progress**: Plans are in the works! I want to have thumbnails of the clock faces displayed so the user can pick and choose which to use. When this is done, I may invest time in giving the user access to different color themes for the clocks.

**Thoughts:** I'm glad I have a set plan now. I really like how the clocks look, but this program lacked some sense in its purpose.

**Link to work:** [clock](https://github.com/Dana94/clock/commit/b0a2243c181db320f799fe03cdff549c6fd8b6ba)

### Day 65: May 11, 2017
##### clock

**Today's Progress**: I made the clocks smaller for the opening page and was able to remove the hands without distorting the other features.

**Thoughts:** Nothing now, still working!

**Link to work:** [clock](https://github.com/Dana94/clock/commit/ec0081731f6cae87c36e4e849c2153eb39bc2758)

### Day 66: May 17, 2017
##### random-quote-machine

**Today's Progress**: Due to my constant additions of quotes, I decided to try and create a text file that will read off the quotes randomly in the program. That way, I will only have to update the text file to add quotes and nothing else.

**Thoughts:** I have never done any sort of file reading in JS before, so I am in unfamiliar territory. : )

**Link to work:** [random-quote-machine](https://dana94.github.io/random-quote-machine/)
This is what I had before the text file plan, I just added gh-pages so it is now public.

### Day 67: May 19, 2017
##### flower-slideshow

**Today's Progress**: Something clicked when I was surfing through MDN and I found the perfect solution to my file uploader. Have the input tag be 'display: none' and it will be triggered by a button that the user is meant to click on when adding an image. I need to look into the src because I had some images directly typed into the js file and are in the images folder in the project. I need to make this work with all image paths.

**Thoughts:** I am so stoked that I made some progress on this since it has been a while. I seem to be gravitating to whatever project I'm in the mood for.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/86be037f47b18784309d352afb531c9049b2d095)

### Day 68: May 25, 2017
##### flower-slideshow

**Today's Progress**: So the "getting the file path to display the uploaded images" is still hard for me. There are soooo many ways to do this. I'm still figuring it out. I'm trying to fix other issues when I see them.

**Thoughts:** I realized that when I minimized the screen to mobile, the grid layout will stay until the page is reloaded. I need it to automatically know that it should be in column form in a smaller screen.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/4a7952ff6af769ce63c09a30606aad3d85d02416)

### Day 69: May 26, 2017
##### flower-slideshow

**Today's Progress**: Today I created a timer so the window size can be checked in case the gallery should be in column form for mobile screens. Also, I got the images uploaded! I got the code mostly from resources (which I noted in the file). Now I need to fix the issue of keeping the images in the gallery when the page is reloaded.

**Thoughts:** That image uploader part took a loooong time to get. I cannot tell you how many websites I bookmarked in order to understand that. I probably need to ask for more clarification though. : )

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/01b9dca6d87dd014c5519637d7ed3ee30ea9f01d)

### Day 70: May 27, 2017
##### flower-slideshow and danaottaviani.github.io

**Today's Progress**: Today I used the same timer from yesterday to also check when any images have been newly uploaded so the program will reload the correct gallery layout to display the new images. I'm a bit concerned about this idea if there are more than 50 images to reupload just because there are just 1 or 2 new ones. I also decided to add icons for the contact info in my resume site as well as my Free Code Camp profile. I was a little hesitant of this one, but as long as it shows my progress, I think it should be there.

**Thoughts:** I need to work on the slider function in danaottaviani.github.io. When it scrolls it cuts off a little of the top of the section it is scolling to. This may be from the new data I added, maybe the spacing needs to be fixed in the top or something.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/9e9f20c77e2db73c39de64318e0993b961919e1d)
   [danaottaviani.github.io](https://github.com/Dana94/danaottaviani.github.io/commit/1f6025ca396917769387e9940362a670f9d7cd10)
   
### Day 71: May 29, 2017
##### flower-slideshow

**Today's Progress**: I simply edited some things in the program today. When an image was clicked on to be displayed, the left/right buttons would not move left and right from that chosen image, now it does.

**Thoughts:** I'm going to ask on Free Code Camp about how to save images into the program so they don't disappear after refreshing the page. I also made it live on gh-pages.

**Link to work:** [flower-slideshow](https://github.com/Dana94/flower-slideshow/commit/bf65a17b13a063b5026de178622699f090f58157)

### Day 72: May 30, 2017
##### danaottaviani.github.io

**Today's Progress**: So I started working on the layout for about.html. I really wanted to use parallax again because the design is so cool. I'm thinking that the current resume site may be a link from this about.html page so it won't be the main focus. Everything is kind of up in the air, but I know that it was time to really get a serious portfolio site up and running.

**Thoughts:** I have seen some really cool designs on Free Code Camp and I just wanted to get some inspiration from there to create my own sleek portfolio page. I hope it looks good in the end, I will definitely ask for feedback when it is done.

**Link to work:** [danaottaviani.github.io](https://github.com/Dana94/danaottaviani.github.io/commit/ca9e8505aff3f8a92bc05b9b7f347a9bf3f2c088)

### Day 73: May 31, 2017
##### danaottaviani.github.io and clock

**Today's Progress**: I added the contact icons for the portfolio and played around with the clocks to try to have their individual pages look good in mobile. A friend mentioned that the reason that clicking the clocks is not dislaying their own html page is because I have to do a XMLHttpRequest. I've loaded new pages upon submitting a form and I do not recall doing that before. 

**Thoughts:** I am really having second thoughts about this new about.html layout. I'm considering taking the color scheme and pictures from my resume site and making it into a portfolio instead of a pretty resume. It was orginally meant to show employers some representation of my skill level but I keep coming back to its awesomeness while struggling with the about.html layout. I may just save the index.html file somewhere else and then overwrite it with the new portfolio idea. Once I do more mobile configuring with the clocks, I will get into that XMLHttpRequest thing to understad how to load the chosen clock by the user.

**Link to work:** [danaottaviani.github.io](https://github.com/Dana94/danaottaviani.github.io/commit/eaecb1bdce8337e775aa1856262e0754beb53435),
[clock](https://github.com/Dana94/clock/commit/aa30b3cc315cfa0a43a013bd16734a4f6b9be9cd)

### Day 74: June 4, 2017
##### clock

**Today's Progress**: Doing some mobile work. Nothing looks good yet, I am trying to find a way to minimize the needed media queries.

**Thoughts:** I'm constantly looking for an easier way to center the clocks in different screen sizes. I found something on CSS-tricks but I think because the clocks are in the same class="row", the given .centered class will have them overlap. Maybe I can change the div classes according to the screen size, sort of like how I made the different gallery layouts for the flower-slideshow. 

**Link to work:** [clock](https://github.com/Dana94/clock/commit/a509601dddbd8bafe63965a288de221aa2d32c76)

### Day 75: June 10, 2017
##### clock

**Today's Progress**: Still on mobile.

**Thoughts:** I am reading about vh and vw and seeing if they could work to my advantage. I am so frustrated with the multiple screen sizes and the never-ending cases for customizing them to look good with individual code segments in CSS. 

**Link to work:** [clock](https://github.com/Dana94/clock/commit/d17411e0bf3a91ee29a65f9e2d5e2804da886e65)

### Day 76: June 17, 2017
##### danaottaviani.github.io

**Today's Progress:** I was trying to configure the layout the way I want it but it just seems, I don't know, too typical? I need to read up about what makes a great portfolio site attract people and look at others to accumulate different styles into my own site. I believe once I have a game plan, I will be more engaged in this project.

**Thoughts:** Sorry it's been a while, I really want to finish these different projects I have. I think I will look into the flower-slideshow server thing since I can also use that for my random-quote-machine too.

**Link to work:** [danaottaviani.github.io](https://github.com/Dana94/danaottaviani.github.io/commit/9c8009b54e9524ce16260371fe62d1c288425a9f)

### Day 77: June 24, 2017
##### Portfolio and Template

**Today's Progress:** Well, after research and drawing out the layout, I am finally trying to create my (long over due) portfolio page. For today I've been picking away at the danaottaviani.github.io code and modifying it to match my design. I also decided to add a template repository since I pretty much use the same libraries all the time. 

**Thoughts:** I plan to work on getting the mLab database set up with my random-quote-machine as I work on my portfolio. I want to have more than one or two projects to show once the site is public. I'm thinking of starting another free language course or perhaps experimenting with SASS as I do my other things. 

**Link to work:** [Portfolio](https://github.com/Dana94/Portfolio/commit/bc91313c65886aa7938ed4cf7cf4358a204dc616), [Template](https://github.com/Dana94/Template/commit/a0198c8b55dd4bf7da25b583b4fd3207c6bd730c)

### Day 78: June 25, 2017
##### Portfolio

**Today's Progress:** My image is giving me some strange margin issues. I believe it's because scaling the image down does not remove the space it would have taken up if it was its original size. Which is a weird concept. I also got connected to my mLab database for my random-quotes-machine. I'm going to make a JSON file with a few quotes and see how it looks uploaded to the database. 

**Thoughts:** I always have trouble with images. This flex-box tool looks like a solution, but the documentation seems kind of daunting. 

**Link to work:** [Portfolio](https://github.com/Dana94/Portfolio/commit/e697aaf610ac75cb22bb88cca404248fc598515d)

### Day 79: July 1, 2017
##### Portfolio and clock

**Today's Progress:** For the portfolio, I tested a different color to possibly go with the dark purple. I like how it looks with the language logos. I decided to change it up with some color so I looked at a site (link in my html code) that has (some) free downloads of programming language icons. I just added HTML5, CSS, and JS. For the clock, I decided to organize my stylesheets with the help of @import so I won't have the same code repeated in numerous files.

**Thoughts:** I'm going to try to code more this coming week. I am usually tired of going on the computer after my job, but I intend to try to code for 30 min or so each day. I want to keep a consistent schedule when it comes to coding.  

**Link to work:** [Portfolio](https://github.com/Dana94/Portfolio/commit/375935673bf6b93fcee43b8c74d30857952092fd), [clock](https://github.com/Dana94/clock/commit/09ccccdec37423b74d04e7254a3de2971ca343de)

### Day 80: July 2, 2017
##### Portfolio

**Today's Progress:** Made the row colors lighter as you go down the screen. Hope it looks good to other viewers. I created the placeholdesr for the projects but I have to work on the spacing and title position. I may decide to have the row titles in the top center instead of the left side. We'll see.

**Thoughts:** When I finish this portfolio, I need to work on the obstacles of the other programs that are keeping me from finishing them.  

**Link to work:** [Portfolio](https://github.com/Dana94/Portfolio/commit/e92b3074ba48301cfee553c1ee14184402971577)

### Day 81: July 9, 2017
##### Portfolio

**Today's Progress:** After practicing with bootstrap, I decided to implement a better way to display the projects. Now I am using an image of one of my apps to see how it will look in the end.

**Thoughts:** I'm deciding whether to have background images in divs or just show images for the project visuals. I want whatever doesn't look distorted on mobile.

**Link to work:** [Portfolio](https://github.com/Dana94/Portfolio/commits/master)

### Day 82: July 16, 2017
##### Portfolio

**Today's Progress:** I was looking at the code for [this portfolio](https://codepen.io/envincebal/full/BRvBOm/) for inspiration and guidance because I was tired of going in circles with the positioning of my project row. Now I am working on making sure the projects aren't too tall in mobile and then trying to figure out what and why is causing there to be a slight margin on the right side of the page. 

**Thoughts:** At first, I was ashamed of looking at someone else's code for the layout of this project. And you know what? I'm not anymore. I have come such a long way and learned so much by examining other people's code. This is a way for me to learn the easier ways to structure my pages without having to go from square one each time. I also put a link to his portfolio in my stylesheet to give credit. :)

**Link to work:** [Portfolio](https://github.com/Dana94/Portfolio/commit/25b65b61e1ae64b860f920e7d002150f0b983dfb)

### Day 83: July 22, 2017
##### Portfolio

**Today's Progress:** I added the contact icons and fixed the language ones so they don't stack until extra small screens.

**Thoughts:** Finally got off my butt and asked questions on Free Code Camp. If anything, this will encourage me to try and see if their solutions help fix my issues during the week, and not wait until the weekend.

**Link to work:** [Portfolio](https://github.com/Dana94/Portfolio/commit/7b71e4f0d6e714b5691ed52d63dd810c90fccadb)

### Day 84: August 12, 2017
##### Portfolio

**Today's Progress:** Making an "ongoing projects" and "completed projects" section of my portfolio.

**Thoughts:** After someone at my job inquired about my front-end experience, I realized that it doesn't hurt to show off merely the design part of some of my projects (even though I don't consider them done yet). I can imagine someone will give me negative feedback about this but honestly, I don't care. It's not like I'm saying they all work yet, I'm proud of how much my html and css have improved, as well as understading Bootstrap. :)

**Link to work:** [Portfolio](https://github.com/Dana94/Portfolio/commit/8d4f25f1509f6a5534cb6414c9c3b755d578bca9)
