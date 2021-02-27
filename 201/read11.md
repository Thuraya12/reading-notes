 # Read11
## From the Duckett HTML book:
## Chapter 16: “Images” (pp.406-427)

#### Controlling size of images in CSS
We can control size of images using **width** and **height** properties in css or use class names are used that determins your pictures' sizes such as small, medium, and large and use them with the width and height properties. Specifying pictures width and height is good when rendering in the browser.
 ### Aligning images in CSS

 Images can be aligned using align attribute or using float property. We can center images by returning them from inline elements to block elements display: block; and then center them with text align property or using marging auto proprety.

 ### Adding background images
 Background images can be used behind any HTML element specifically, or for the whole body, it can be added by typing the selector and then background image property and then set a url with the image path, e.g.*body {backgroung-image: url('images/cat.jpg');}*. There is also a background-repeat property that can be used with four different values:
 1. repeat gets the background images image repeated horizontally and vertically.
 2. repeat-x : reapeats background images horizontally.
 3. repeat-y : repeats background images vertically.
 4. no-repeat: the background images apears once.

 Also we can use backgroung-attachment property with the value **fixed** to make the image stay in the same position when scrolling, or with the value **scroll** so it moves when we scroll. In addition, when ther's no repetition, we can use background-position property to determin the background image place in the browser.

  
## Chapter 19: “Practical Information” (476-492)

### Search engine optimization
Search engine optimization(SEO) is about the visibility of a website on the web and search engines so that the websites apears in the first results when the topic is searched, and this is done by knowing what words people use to search and putting them in the right place so that the browser access it when searched and this is called **on-page techniques**, also the browser looks for how many sites link your site in theirs and how much their sites are relevant to your topic which is called**off-page techniques**.
### Using analytics to understand visitors
When a webiste starts to have visitors it must make analysis about how they reached your site and what content they seek and when do they leave, this can be done using a service offered by google called **google analytics**. you create an acount on google analytics and use a **tracking code** on every page of your website and the tracking data gets stored on google servers and you can access it o see how your site is used.The tracking code must be placed before the closing tag of the head element.
### Putting your site on the web
If you want to publish your site on the web you need a domain name and a web hosting. **The Domain Name** is your web address, e.g. google.com, and you can get a domain name from websites thet offer this service and you pay them anually. **The web hosting** is the web server where you upload your website so that people can see it, these servers are special computers that are continuously connected to the internet so they always allow access to the requested websites stored on them.

## MDN article about audio and video elements.
Video and audio tags are used in html5 to embed audio and video to your website, for playback control you can use **controls** attribute. **The HTMLMediaElement API** is used also to control audio and video using the play and pause by using HTMLMediaElement.play(), and  HTMLMediaElement.pause(), and it is used with both <audio> and <video> elements.

## Chapter 9: pages 201-206 
 **Flash is no longer supported by many browsers but is an important part of history**.
 
 ### How to add Flash movies into your site
 flash is popular for adding audio and video to websites,but it started as a tool for adding animation, and wheather you add animation or mediaplayer it is considered as **Flash movies** . To create Flash movie we have to download the paid flash software from adobe but there are other companies that offer flash for free.
 When you create a flash file it gets saved with .fla extension but when used on the web it has a .swf extension. The code created when exporting the movie used to be imbeded in html elements **object** and **embed**, now it is imbeded using javascript.
 
 ### HTML5 <video> and <audio> elements
 Flash became to be used fewer among website because many things has been launched that made the making of animation easier such as javascript libraries of prototype, script and jQuery. And now HTML5 is more used instead because is supports **audio** and **video** tags. 


