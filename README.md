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

## 1.4 Website Planning and Wireframes

![User Stories](https://i.imgur.com/fn7KZba.png)

![Data Architecture](https://i.imgur.com/DHOopcQ.png)

![Wireframe](https://i.imgur.com/28dFqtY.png)

![Design elements](https://i.imgur.com/glU3pRn.png)

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

For larger screens this is moved to the bottom of the page, and a donate button replaces the ability to dismiss the alert. to make better use of screen space.

## 2.4 Welcome section

A welcome section includes a welcome text, which is reduced for smaller screens, and a video introduction to the resources.

## 2.5 Shows section

The shows section features a Bootstrap carousel displaying a screen width card for each show streaming. The carousel scrolls between slides every 5 seconds.
The card contains information about each show, and uses alerts to attract attention to new shows, or shows coming soon.
Addionally each card contains a YouTube iframe with the ability to watch the show without leaving the page.

## 2.6 Stories section

The stories section features a horizontal scroll of all the stories being created. This saves sceen space scrolling, and ties into standards of horizontal scrolling for video selection which is currently widely deployed on popular video sites.

## 2.7 Projects section

The projects are multi video or document sections, so have been placed into an accordian showing one project at a time. The "episodes" of the projects are in a horizontal scroll, echoing the stories sections.

## 2.8 Makes section

The makes section features cards in a masonry style column of cards which link to PDF downloads or Youtube videos of activities for kids.
The cards a filterable using a filter on the page for activities suitable for older/younger children, or for video entries. This feature is created through show/hide variables using CSS only.

## 2.9 Footer

The footer contains social media links. For larger screens in which the donate alert is shown at the bottom of the screen, it uses a media query to add padding added to raise it above the donate alert.

## 2.10 General features

For accessibility the active link is highlighted in the same colour as the section of the page. This includes contrast as the deafault blue doesn't show well against the background, but also includes accessibility into the design thought process.

### 2.11 Future improvements

- Video playback: As there's a lot of video on the page, it would be helpful if a script could be applied to ensure playing one video would pause all others.
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

# 4 Testing

## 4.1 Validation

### HTML5 validator

Validates the code aheres to HTML standards

The HTML validator throws up a warning about a double hyphen in a comment, however as this is part of URL to copied code, I have left it in place.

![Screenshot of HTML warning](https://i.imgur.com/71C5dCI.png)

### CSS validator

Validates the code aheres to CSS standards.

The code has been run through the W3 CSS validator.

It has thrown up some issues with the use of variables, however further research implies this is a feature not supported by the validator: https://github.com/w3c/css-validator/issues/111

Manual testing shows the code responding on the webpage as anticipated:

![GIF showing select boxes changing colour on hover and the filter operating as expected](https://i.imgur.com/VibCtU2.gif)

Additonally the validator highlighted the use of some "Unknown Vendor Extnensions". These are browser specific extensions, namely Safari and Internet Explorer.

![CSS validator warnings](https://i.imgur.com/bkfq6yA.png)

### [Contrast validator](https://color.a11y.com/Contrast/)

The contrast validator checks contrast between text and background to ensure it's visible to people with vision impairments.

One issue was found on the site, but on further eximanation, it references a hidden form, and as such is not visible to any user.

[Colour Contrast result](https://i.imgur.com/LguREGJ.png)

## 4.2 UX Stories

// Write about how each part of your responsive website behaves on different screen sizes.
And if you want to knock the grade for testing all the way up to the max:

## 4.3 Manual Testing

// Manually go though every part of your site and write out how you confirmed that each link, hover effect and other interactive parts of the site work as you expect.

## 4.4 Bugs

### Active Bugs

- A [script was found](https://stackoverflow.com/questions/52924820/pause-bootstrap-carousel-when-playing-youtube-video) to prevent carousel scrolling while video was playing and to pause the video on manual control to the next page. However it required Bootstrap 4.4.1, which broke other Bootstrap functionality on the page. Ideally a fix can be found.

### Squashed Bugs

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
