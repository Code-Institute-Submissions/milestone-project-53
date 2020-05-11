# 1. UX

## 1.1 Who is this website for?

This website is for parents and their children stuck at home due to school closures. It additionally for the theatre continue it's education and creative resources while the building is closed.

## 1.2 What is it that they want to achieve?

They can come to the site for ideas on how to entertain their children with content such as read stories, mini-shows, projects and makes.

## 1.3 How my project is the best way to help them achieve those things?

The website collates the output currently being created and posted in various places into one portal.

The website provides:

- A welcome section with video explaining the content, and the current context.
- Current shows streaming, with creative information available.
- A scrollable selection of stories for children.
- A selection of longer multi day projects for children to partake in.
- A filterable selection of craft makes.
- The website also prompts for donations, and links back to the main theatre site.
- A styling desgined to tie in with the main theatre site.

## 1.4 Website Wireframes

//

# 2. Features

This Website features:

## 2.1 Top Section

A header based on the original Little Angel Website (http://littleangeltheatre.com).

Its built to Aesthetically tie this site into the main site and includes the original navigation links to the main website pages. The text of links changes colour on hover, as per original site.

For mobile, just the logo is displayed.

## 2.2 Nav Bar
Below this is a sticky nav bar which sticks to the top of the screen once the main header scrolls off the page. 

This features quick navigation to all the sections on this website, along with social media sites. The links change colour on hover as a continuation of the header. For mobile screens, the social media links are dropped, and the text so just icons are used in the bar.

## 2.3 Donate Alert
Below the nav bar is a dismissable donate request which only loads on first entry to the site. 

For larger screens this is moved to the bottom of the page, and a donate button replaces the ability to dismiss the alert.

## 2.4 Welcome section
A welcome section includes a welcome text, which is reduced for smaller screens, and a video introduction to the resources.

## 2.5 Shows section
The shows section features a Bootstrap carousel displaying a screen width card for each show streaming. The carousel scrolls between slides every 5 seconds.
The card contains information about each show, and uses alerts to attract attention to new shows, or shows coming soon.
Addionally each card contains a YouTube iframe with the ability to watch the show without leaving the page.
JavaScript has been used to makes sure the carousel stops scrolling while the video is playing, and that the video will stop if the user manually slides to the next slide.

## 2.6 Stories section

## 2.7 Projects section

## 2.8 Makes section
The makes section features cards in a masonry style column of cards which link to PDF downloads or Youtube videos of activities for kids.
The cards a filterable using a filter on the page for activities suitable for older/younger children, or for video entries. This feature is created through show/hide variables using CSS only.

## 2.9 Footer
The footer contains social media links. For larger screens in which the donate alert is shown at the bottom of the screen, it uses a media query to add padding added to raise it above the donate alert.

## 2.10 General features
For accessibility the active link is highlighted in the same colour as the section of the page. This includes contrast as the deafault blue doesn't show well against the background, but also includes accessibility into the design thought process.

### 2.11 Future improvements
- Nav Bar indication of active location on page would have been a nice feature. This was considered too late into the project to implement.
- The theatre is getting a lot of feedback with many children sending in their creations, as such a gallery page to exhibit these may be a nice idea.
- JavaScript could be used to make the filters for makes more user friendly, and could combine filters allowing for more detailed categories, perhaps based around the common materials used in the makes, or the time required. This is beyond the scope of this project.
- As more makes are added, it will make the page longer, perhaps calling for pagination or infinate scroll. This is beyond the scope of this project.

# 3. Technologies Used


## 3.1 Languages

### HTML/HTML5

Semantic HTML 5 has been used for the web markup.

### CSS/CSS3

CSS/CSS3 to has been used to provide styling.

### JavaScript

A few snippets of JavaScript have been used to improve the user experience.

## 3.2 Frameworks

### BootStrap 4

Bootstrap 4 components were used to save time on devolping the website.

## 3.3 Integrated Development Environment

### Gitpod

Gitpod was used as the IDE for this project.

## 3.4 External Hostings

#### GitHub
The project used the GitHub hosting service to save the project in a repository.

#### Little Angel Theatre
Many of the resources used in the site (PDF downloads, Header images) are hosted on the Little Anger Theatre domain.

### Imgur
Imgur service to hosts images and screen shots for the ReadME.


## 3.5 Other Tools

### Balsamiq Wireframes

Wireframes built using Balsamiq.

### Fonts

Fonts OSP-DIN and Lato hosted from https://fontlibrary.org/

### Images

Images used on this site were run through http://tinypng.com for compression.

# Testing
### HTML5  validator
The HTML validator throws up a warnign about a double hyphen in a comment, however as this is part of URL to copied code, I have left it in place.

![Screenshot of HTML warning](https://imgur.com/NaA2Qch)

### CSS validator
The code has been run through the W3 CSS validator.

It has thrown up some issues with the use of variables, however further research implies this is a feature not supported by the validator: https://github.com/w3c/css-validator/issues/111

Manual testing shows the code responding on the webpage as anticipated:

![GIF showing select boxes changing colour on hover and the filter operating as expected](https://imgur.com/CXpKELg)

Additonally the validator highlighted the use of some "Unknown Vendor Extnensions". These are browser specific extensions, namely Safari and Internet Explorer.

![CSS validator warnings](https://imgur.com/PIA2Vze)

# Deployment 


# Credits
## Code snippets
- Little Angel Header: https://littleangeltheatre.com/
- Sticky Header: https://css-tricks.com/creating-sliding-effects-using-sticky-positioning/
- Carousel: https://mdbootstrap.com/snippets/jquery/alexpiffero-it/696600
- Stories scroll: https://www.freecodecamp.org/news/horizontal-scrolling-using-flexbox-f9d16817f742/
- Card Filter: https://webdesign.tutsplus.com/tutorials/how-to-build-a-filtering-component-in-pure-css--cms-33111
- Youtube stop carousel JS script: https://stackoverflow.com/questions/47079195/youtube-video-iframe-in-a-bootstrap-carousel-stop-carousel-from-sliding-when-v

## Content

Content is taken from various pages and press releases on https://littleangeltheatre.com/

## Media

Media has all come from Little Angel Theatre.
Background photo of Little Angel's 2018 production of Angelo. Photo by Ellie Kurttz.

## Acknowledgements

I received inspiration for this project from Little Angel Theatre, and would like to thank Sophie Waddy for providing resources and a remit.

I would also like to thank Akshat Garg for his support as a mentor and Cormac Lawlor for his support as Code Institute Tutor.
