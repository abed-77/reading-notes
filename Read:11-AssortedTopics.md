# Chapter 16: “Images” (pp.406-427)

    - You can specify the dimensions of images using CSS This is very helpful when you use the same sized images on several pages of your site.
    - Images can be aligned both horizontally and vertically using CSS.
    - You can use a background image behind the box created by any element on a page.
    - Background images can appear just once or be repeated across the background of the box.
    - You can create image rollover effects by moving the background position of an image.
    - To reduce the number of images your browser has to load, you can create image sprites.

# Chapter 19: “Practical Information” (476-492)

    - Search engine optimization helps visitors find your sites when using search engines.
    - Analytics tools such as Google Analytics allow you to see how many people visit your site, how they find it, and what they do when they get there.
    - To put your site on the web, you will need to obtain a domain name and web hosting.
    - FTP programs allow you to transfer files from your local computer to your web server.
    - Many companies provide platforms for blogging, email newsletters, e-commerce and other popular website tools (to save you writing them from scratch.

# MDN article on audio and video elements

    The HTMLMediaElement API makes a wealth of functionality available for creating simple video and audio players, and that's only the tip of the iceberg.

    Here are some suggestions for ways you could enhance the existing example we've built up:

        The time display currently breaks if the video is an hour long or more (well, it won't display hours; just minutes and seconds). Can you figure out how to change the example to make it display hours?

        Because <audio> elements have the same HTMLMediaElement functionality available to them, you could easily get this player to work for an <audio> element too. Try doing so.

        Can you work out a way to turn the timer inner <div> element into a true seek bar/scrobbler — i.e., when you click somewhere on the bar, it jumps to that relative position in the video playback? As a hint, you can find out the X and Y values of the element's left/right and top/bottom sides via the getBoundingClientRect() method, and you can find the coordinates of a mouse click via the event object of the click event, called on the Document object