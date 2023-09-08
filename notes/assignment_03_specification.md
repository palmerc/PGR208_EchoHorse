## Assignment 3 - Echo Horse

[GitHub PGR208 Echo Horse](https://github.com/palmerc/PGR208_EchoHorse.git)

In Assignment 2 we built an Echo client for text. Let's extend that to send images and display the result. In the end we should have an animated running horse. 

In the late 19th century there was some debate on how a horse runs. Does a horse's feet leave the ground? Eadweard Muybridge, set up a camera to find out and produced [The Horse in Motion](https://en.wikipedia.org/wiki/The_Horse_in_Motion).

![The Horse in Motion](resources/the_horse_in_motion.jpg)

The app will use the provided images, sending one frame to the echo server and then display the response. If you tap the send button fast enough it might even look like it is running and if it is really fast it my look a bit like Odin's horse [Sleipnir](https://en.wikipedia.org/wiki/Sleipnir). To make it as fast as possible we'll have a Repeat button that will make the images repeat endlessly as soon as one message is returned, we send the next one.

![So many legs](resources/sleipnir.jpg)

We also want to maintain the original functionality of text sending, such that it should repeat endlessly the last message received if repeat mode is enabled.

### An App Icon

I have provided an SVG (Scalable Vector Graphic) that you can use as an app icon. It doesn't have to be this one, or you can modify it, but I want you to have an app icon this time. You may need to convert this asset to a PNG bitmap at a variety of different sizes.

![The Horse SVG](resources/Horse.svg)

### The App Design Sketch

![The application design](resources/assignment_03_design.png)

### Submission

Clean your project and Zip it and upload to Canvas. Alternatively, upload it to Github and send the link to the Canvas assignment. Also use the Screenshot app or similar to take a movie of your app in action. This is either uploaded to Canvas or added to the
 git repository.

