# The Monkees Band Website #
### First Milestone Project ###
***
## Aim ##  
   
 The aim of this site is to build a _static_ (front-end only) website, with 4-5 pages, for [**The Monkees**](https://michael-leese.github.io/first_milestone_project_band/).  
 Using _Wireframes_ to responsively design the 
 site in a _mobile-first_ design approach. We have been provided with some assets in the form of audio, video and images that the band would like to include and
 have also been asked to source some additional peices to fullfil the _UX_ we would like the visitors to experience.
 We have had an interview with the client that has expressed some _user stories_ to us, as well as some key features they 
 would like to include.  
 * Primary ordience is Fans and Potential Fans.
 * Other audiences are people wishing to book bands for events such as Weddings and Christmas Parties.
 * The would like the multi-media provided to be used, images, audio and video.
 * Ability to create a social media presence.

***
## UX ##  
 The User eXperience was fundamental to my design process, starting with a _Mobile First Design_
 approach I created _Wireframes_ (which are included in the Wireframes folder in the 
 [Github Repositary](UX/Wireframes).) and also some _User Stories_ based on the information 
 provided in the interview.
 
 1. As a Fan I want to watch any videos of the band.
 2. As a Fan I want to listen to some of their back catalogue of songs.
 3. As a Fan I want to see when they are next on Tour.
 4. As a Fan I want to keep up with the latest news and new material.
 5. As a Fan I want to follow them on Social Media.
 6. As a Potential Fan I want to listen to their music to see if I like them.
 7. As a Potential Fan I want to watch to watch a video and see if I want to see them live.
 8. As an Events Organiser I want to see a video and check their followings to see if I like their performance and book them.
 9. As an Events Organiser I want to contact the band and Check availability and prices by messaging.  
 
I have kept the site easily navigated, as simply as possible, so if a Potential Fan is converted to Fan, on a page they can carryout a Fan User story, having been converted from Potential Fan to Fan.
As this is not intended to be a back end site the modals are for show only at the moment for experiencing the affect.
We created a site that has 5 pages in total, with external links opened in a new window, so as to ensure our page never dissapears from the Browser.
Upon researching different existing bands websites, _inspiration_ for the background video on the homescreen, with a Signup Button for Newsletter came from
[Oasis](www.oasisinet.com) Band Site. Featuring a video and links to news and new material on the callout section. 
 
***
## Features ##

The various features created on the website are:
* On every screen the Nav has Logo that links to the Home Screen, a Burger Menu, which is visible on smaller and medium screen sizes and Nav Menu on larger screen sizes only.
* The Nav options are *underlined* depending on what page you are on, for UX the links are highlighted and the cursor changes to a pointer.
* All Buttons, the cursor changes to a pointer and background highlighted for UX.
* On every screen with a fixed footer their is the abilty to follow the band on social media, so as if Fans, Potential Fans or Event Organisers may check out the presence from any point their User Stories are converted.
* A background video on the [Home](index.html) Page, with a _Sign Up_ button for newsletter via email.
* On the [Band](band.html) Page the images, as on all the other pages are responsive.
* On the [Music](music.html) Page the songs are controllable to play/pause with controls.
* On the [Media](media.html) Page the videos are controllable to play/pause with controls.
* On the [Gigs](gigs.html) Page the _Buy Now_ button links to www.ticketmaster.co.uk and the _Book Now_ button goes to a modal, contact form.

The features allow all of the User Stories to be fulfilled and information collected, in the form of newsletter and Booking Form. Information on Ticket Sales will come from www.ticketmaster.co.uk. 
Social Media Presence will be indicated via the followers on the various brands, [Youtube](www.youtube.com), [Twitter](www.twitter.com), [LinkedIn](www.linkedin.com) and [Facebook](www.facebook.com).  
  
Future development may come in the form of a back end program so as to collate and use the information provided.

***
## Technologies Used ##
 For this project the Technologies used included;
 * Cloud9 IDE for development.
 * HTML5
 * CSS3 using Flex Box.
 * Bootstrap for Modal Pop Up only.
 * Javascript and Jquery for the Modal Pop Up only.
 * Fontawesome for Social Media Glyphicons.
 * Google Fonts for Font styles.
 * Markdown for README.md file.
 * BASH
 * Ubuntu
 * GIT
 * GITHUB
 * Google Chrome Developer Tools.
 * Firefox Developer Tools.
 * Microsoft Edge Developer Tools.
 * Iphone for testing on real IoS system as I am on Windows.
 * Slack for feedback.
 * [TinyPNG](https://tinypng.com/) for compressing images.
 
***
## Testing ##  

I tested my code, using various platforms Google Chrome, FireFox and Microsoft Edge developer tools;

* Google Chrome developer tools used to develop the site, using the _responsive design mode_ to view over multiple screen sizes for UX design requirements.
   * I used the following responsive screen sizes in the developer tool:
     * Galaxy S5
     * PIXEL 2
     * PIXEL 2XL
     * Iphone 5/SE
     * Iphone 6/7/8
     * Iphone 6/7/8 Plus
     * Iphone X
     * Ipad
     * Ipad Pro
* I also tested the compatibility of the site live(real world) via GITHUB Pages on:
   * Galaxy A5
   * Iphone 5 and 8
   * Sony Xperia(Android) tablet 
   * MSI laptop 15.5" screen 
   * Phiilips HD Desktop 21" monitor
     
   
* The Developer Tools did not reflect the real world experience on testing, so adjustments had to be made for the real world experience on devices.
   * With Microsoft Edge the #Color used for the styling of the News button didnt render correctly so converted it to an rgba value.
   * With Firefox it was inputting some text at top of media and music page to inform user to double-click to play/pause as on chrome is just one click.
   * With Iphone 5 (real world) the height was required as an attribute so full height of audio controls could be seen.
   * Iphone 8, Galaxy A5 and sony Xperia Tablet, all had to have additional margins or paddings input for viewport(real world).
 
I went through the site and clicked on each feature, Logo(link), Glyphicon Links, Buttons and audio/video controls to ensure
that they worked. For Firefox users I added instructions to the top of the page (Firefox users double-click to play/pause) as this differed from Chrome and Microsoft Edge, this was due to feedback from testers on Slack. The Modal forms that have come up I have tested to ensure that they only work if the required information is input and they close upon 
submition.  
I used Slack to post my GITHUB link and get feedback from the forum and individuals I had collaborated or spoken with previously.  
I proof read the pages with my wife, to avoid grammatical errors and spelling mistakes.  
I took on board some of the comments from testing such as identifying on Navmenu or BurgerMenu as to your current location, Burger Menu 
being vertically aligned as opposed to horizontal.  
  
I utilised [HTML Validator](https://validator.w3.org/) and [CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
to ensure that my code was correct and that their were no errors.

***
## Deployment ##

The website was deployed using Cloud9 IDE and using Ubuntu and BASH in order to create traceable development versions upon uploading them to GITHUB.  
The GITHUB repository was deployed on GITHUB Pages, this is the deployed site, [The Monkees](https://michael-leese.github.io/first_milestone_project_band/index.html).  
I have created seperate [commits](https://github.com/michael-leese/first_milestone_project_band/commits/master) for each peice of functionality and testing procedure under taken.

***
## Credits ##

### Content ###
Information regarding the Band and the Individual Members was taken from [Wikipedia](https://en.wikipedia.org/wiki/The_Monkees).  
  
Code Snippets:  
[Bootstrap](https://getbootstrap.com/docs/3.3/javascript/#modals) was used to to provide the _Modal_ forms only, along with [Jquery](https://code.jquery.com/).  
All responsivness was carried out using _Flex Box_ in CSS.  
All code snippets have been restyled or worked to suit The Monkees site needs.  
Help from following places:  
* For elements and attributes https://www.w3schools.com.   
* Checkbox and Label, Burger Menu https://codepen.io/elgreg/pen/rGgfF restyled and coded to suit my design.
* Getting button to open link in new page https://stackoverflow.com/questions/34082002/html-button-opening-link-in-new-tab.


### Media ###  

The media was supplied via a [GITHUB Repository](https://github.com/Code-Institute-Org/project-assets) as well as through research on the web.  
Images uploaded locally were ran through https://tinypng.com/ so as to compress the files before uploading to the IDE.  
The Monkees additional image/video sources:  
* Logo Image
  * https://www.bandlogojukebox.com/blog/2017/12/4/m1-the-monkees 
* 60’s Girl Image
  * https://archive.org 
* 60s Couple Image
  * https://www.flickr.com 
* Background Image Wallpaper
  * https://www.vectorstock.com/royalty-free-vector/red-spiral-design-background-vector-16316912  
* Additional videos
  * www.tubeoid.co (The Monkees Behind the Scenes(2000))
    * video was cropped and saved using www.hesetube.com
  * https://archive.org/ (Im a Believer video)

Fonts were taken from [Google Fonts](https://fonts.google.com/) in the 
form of [Coiny](https://fonts.google.com/specimen/Coiny) and [Fugaz One](https://fonts.google.com/specimen/Fugaz+One), the default language was Sans-Serif.


### Acknoledgements ###

I have to acknowledge the following people for assistance with code snippets and functionality:
* Button element to act like a link https://stackoverflow.com/questions/2906582/how-to-create-an-html-button-that-acts-like-a-link
* Button Form Target https://www.w3schools.com/tags/att_button_formtarget.asp
* I gained useful insight into Elements and attributes from https://www.w3schools.com 
* Ensuring video autoplayed on Iphone(IoS) https://stackoverflow.com/questions/43570460/html5-video-autoplay-on-iphone
* Change _Padding_ to zero on modal buttons as IoS default is 1em https://stackoverflow.com/questions/44941161/safari-on-ios-cant-render-button-text-center-aligned