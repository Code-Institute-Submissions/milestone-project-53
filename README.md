# Table of Contents

## [1. UX](#1.-UX)

[1.1 Who is this website for?](##1.1-Who-is-this-website-for?)

[1.2 What is it that they want to achieve?](##1.2-What-is-it-that-they-want-to-achieve?)

[1.3 How my project is the best way to help them achieve those things?](##-1.3-How-my-project-is-the-best-way-to-help-them-achieve-those-things?)

[1.4 Website Planning and Wireframes](##-1.4-Website-Planning-and-Wireframes)

## [2. Features](#2.-Features)

[2.1 Top Section](##-2.1-Top-Section)

[2.2 Nav Bar](##-2.2-Nav-Bar)

[2.3 Donate Alert](##-2.3-Donate-Alert)

[2.4 Welcome section](##-2.4-Welcome-section)

[2.5 Shows section](##-2.5-Shows-section)

[2.6 Stories section](##-2.6-Stories-section)

[2.7 Projects section](##-2.7-Projects-section)

[2.8 Makes section](##-2.8-Makes-section)

[2.10 General features](##-2.10-General-features)

[2.11 Future improvements](###-2.11-Future-improvements)

## [3. Technologies Used](#-3.-Technologies-Used)

[3.1 Languages](##-3.1-Languages)

[3.2 Frameworks](##-3.2-Frameworks)

[3.3 Integrated Development Environment](##-3.3-Integrated-Development-Environment)

[3.4 External Hostings](##-3.4-Externa-Hostings)

[3.5 Other Tools](##-3.5-Other-Tools)

## [4. Testing](#-4.-Testing)

[4.1 Validation](##-4.1-Validation)

[4.2 UX Stories](##-4.2-UX-Stories)

[4.3 Manual Testing](##-4.3-Manual-Testing)

[4.4 Responsive Features](##-4.4-Responsive-Features)

[4.5 Testing on network speeds](##-4.5-Testing-on-network-speeds)

[4.6 Bugs](##-4.6-Bugs)

## [5. Deployment](#-5.-Deployment)

## [6. Credits](#-6.-Credits)

[6.1 Code-snippets](##-6.1-Code-snippets)

[6.2 Content](##-6.2-Content)

[6.3 Media](##-6.3-Media)

[6.4 Acknowledgements](##-6.4-Acknowledgements)

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

### 3.1.1 HTML/HTML5

Semantic HTML 5 has been used for the web markup.

### 3.1.2 CSS/CSS3

CSS/CSS3 to has been used to provide styling.

### 3.1.3 JavaScript

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

### giphy

Giphy makes and hosts giphs for the ReadME.

## 3.5 Other Tools

### Balsamiq Wireframes

Wireframes built using Balsamiq.

### Fonts

Fonts OSP-DIN and Lato hosted from https://fontlibrary.org/

### Icons

Icons are from https://fontawesome.com/

### Images

Images used on this site were run through http://tinypng.com for compression.

# 4. Testing

## 4.1 Validation

### [HTML5 validator](https://validator.w3.org/)

Validates the code aheres to HTML standards

The HTML validator throws up a warning about a double hyphen in a comment, however as this is part of URL to copied code, I have left it in place.

![Screenshot of HTML warning](https://i.imgur.com/71C5dCI.png)

### [Image validation](https://validator.w3.org/)

Additional validation from confirms all images have "alt" caption.

[Report here](assets/docs/images.md)

### CSS validator

Validates the code aheres to CSS standards.

The code has been run through the W3 CSS validator.

It has thrown up some issues with the use of variables, however further research implies this is a feature not supported by the validator: https://github.com/w3c/css-validator/issues/111

Manual testing shows the code responding on the webpage as anticipated:

![GIF showing select boxes changing colour on hover and the filter operating as expected](https://i.imgur.com/VibCtU2.gif) [external gif link](https://imgur.com/VibCtU2)

Additonally the validator highlighted the use of some "Unknown Vendor Extnensions". These are browser specific extensions, namely Safari and Internet Explorer.

![CSS validator warnings](https://i.imgur.com/bkfq6yA.png)

### [Contrast validator](https://color.a11y.com/Contrast/)

The contrast validator checks contrast between text and background to ensure it's visible to people with vision impairments.

One issue was found on the site, but on further eximanation, it references a hidden form, and as such is not visible to any user.

![Colour Contrast result](https://i.imgur.com/LguREGJ.png)

## 4.2 UX Stories

### A Parent wants to homeschool and is looking for an educational project

1.  Click on projects in menu bar
1.  They will be presented with some information about projects and (currently) a choice of 2 to choose from.
1.  On choosing a project the steps are broken down into videos with daily activities which build to a show at the end and teach making skills.

![Desktop demonstration](https://media.giphy.com/media/XEs5aQIcdZEUr9903y/giphy.gif)

### A Parent wants to find out more about the shows streaming.

1.  Click on shows or stories in the menu bar
1.  They will be presented either a selection of short shows which are being streamed, or an array of stories which are being added to daily.
1.  The show tiles include credits for information.

![Desktop example](https://media0.giphy.com/media/Yrfk9mYHKNVAq0Jsz6/giphy.gif)

### A Parent wants to entertain their child so that they can get on with something

1.  Click on shows or stories in the menu bar
1.  They will be presented either a selection of short shows which are being streamed, or an array of stories which are being added to daily.
1.  The child can then peruse at will and hopefully remain preoccupied.

![Desktop Example](https://i.imgur.com/8sYsS4U.gif) [external host link[(https://imgur.com/8sYsS4U)

### A Parent is looking for inspiration for a craft/activity with their child to spend quality time with their child

1.  Click on makes in the menu bar
1.  They are presented some information on basic craft supplies that can be recycled from common household waste which make up the essentials for the crafts section.
1.  They can then choose, and click on a make which will provide a YouTube or written tutorial.

![Desktop Example](https://media.giphy.com/media/S99X26zc9GjrlWsOqv/giphy.gif)

### A Parent wants to donate to the organisation.

1. Click on donate in the menu bar (or on desktop the dontate button at the bottom of the screen).
1. This will open the doantion page of the main Little Angel Theatre website where donations can be made through the ticketing system.

![Desktop demonstration](https://media2.giphy.com/media/Y34vGpX1cHP22uTw9M/giphy.gif)

### A Parent wants to find out more about the shows streaming.

![Desktop example](https://media0.giphy.com/media/Yrfk9mYHKNVAq0Jsz6/giphy.gif)

// Write about how each part of your responsive website behaves on different screen sizes.
And if you want to knock the grade for testing all the way up to the max:

## 4.3 Manual Testing

### Links - External

[Check external links open in new tabs and link to correct URL](docs/external-link-testing.md)

### [Compatibility Report](https://try.powermapper.com/demo/Report/c74986ce-1e2b-4cbb-99bb-0cd92cf02a0c)

| -            | IE 11     | Edge 79   | Firefox 72 | Safari ≤ 12                           | Safari 13 | Opera 66  | Chrome 79 | iOS ≤ 11  | iOS 12    | Ios 13    | Android 3                             | Android 4 |
| ------------ | --------- | --------- | ---------- | ------------------------------------- | --------- | --------- | --------- | --------- | --------- | --------- | ------------------------------------- | --------- |
| Critical     | no issues | no issues | no issues  | no issues                             | no issues | no issues | no issues | no issues | no issues | no issues | no issues                             | no issues |
| Major Issues | no issues | no issues | no issues  | no issues                             | no issues | no issues | no issues | no issues | no issues | no issues | no issues                             | no issues |
| Minor Issues | no issues | no issues | no issues  | `fig` and `figcacption` not supported | no issues | no issues | no issues | no issues | no issues | no issues | `fig` and `figcacption` not supported | no issues |

#### Hovers

Checking links show correct colour and use correct transition timings

[Progress report here](docs/hover-testing.md)

Desktop demonstration of hovers, random links and features working on the site using Chrome:
![Desktop demonstration of hovers, random links and features working on the site using Chrome](https://i.imgur.com/3Ho8z6k.gif)
[external host link](https://imgur.com/3Ho8z6k)

![Desktop demonstration of hovers, random links and features working on the site using Safari](https://i.imgur.com/PS6CwFS.gif)
[external host link](https://imgur.com/PS6CwFS)

### Links - Internal

Check internal links work and reference correctly

[Progress report](docs/internal-link-testing.md)

### Proofread

- [x] Spelling checked via https://www.internetmarketingninjas.com/online-spell-checker.php
- [x] Maually Proof read

## 4.4 Responsive Features

All responsive features are working. The gif below deomnstrates testing on iphone 8.
Expected responsive features:

- [x] Header logo central
- [x] navbar Logos only
- [x] navbar no social media links
- [x] Dismissable donate alert
- [x] welcome video below text
- [x] Curtailed welcome text
- [x] shows carousel functioning
- [x] shows text below videos
- [x] Project episode headings cutailed to before the colon
- [x] Project episode body text hidden
- [x] Abridged Activities introduction text
- [x] Responsive number of make tile columns
- [x] No body text on make cards
- [x] No donate footer at bottom of page

### Testing Responsive Features: Mobile version (iphone 8)

![iphone responsiveness testing](https://i.imgur.com/o7sNLsc.gif)
[external host link](https://imgur.com/o7sNLsc)

![Safari browser respnsive demonstation](https://i.imgur.com/8M4Icpq.gifv)
[external host link](https://imgur.com/8M4Icpq)

A bug was found that `background-attachment: fixed` is disabled on iOS. This has been added to the bugs list.

## 4.5 Testing on network speeds

## 4.6 Bugs

### Active Bugs

- [ ] Project 2 card 1 size
- []on iphone background image not sticky

### Squashed Bugs

- [x] A [script was found](https://stackoverflow.com/questions/52924820/pause-bootstrap-carousel-when-playing-youtube-video) to prevent carousel scrolling while video was playing and to pause the video on manual control to the next page. However it required Bootstrap 4.4.1, which broke other Bootstrap functionality on the page. Ideally a fix can be found.
- [x] Projects download shouldn't underline on hover
- [x] Filter tags download shouldn't underline on hover
- [x] Filter tags shouldn't link to home
- [x] Filter tags should center
- [x] Project download links
- [x] Borders on story videos
- [x] Story video size
- [x] No video makes
- [x] Sticky carousel arrows
- [x] Makes filter tracks to begininning of activities
- [x] carousel chevrons cover text
- [x] carousel chevrons active border looks ugly
- [x] iframes lacking titles for screen readers
- [x] href telephone number
- [x] bad crop on goldilocks bear image

# 5. Deployment

Repo URL: https://github.com/c-marsh/milestone-project-1.

1. Using Gitpod's Chrome extension, the project was launched from within the repository, based on [CodeInstitutes template](https://github.com/Code-Institute-Org/gitpod-full-template).
1. Code was developed through Gitpod’s IDE, and develpoments regularly commited and pushed to the Github repository.
1. A branch was created to experiment with some code conflicts, and was merged back into the master branch once bugs were ironed out.

The project be viewed by following this URL: https://c-marsh.github.io/milestone-project-1/, or run locally by following [these instructions](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

# 6. Credits

## 6.1 Code snippets

- Little Angel Header: https://littleangeltheatre.com/
- Sticky Header: https://css-tricks.com/creating-sliding-effects-using-sticky-positioning/
- Carousel: https://mdbootstrap.com/snippets/jquery/alexpiffero-it/696600 and https://stackoverflow.com/questions/52924820/pause-bootstrap-carousel-when-playing-youtube-video
- Stories scroll: https://www.freecodecamp.org/news/horizontal-scrolling-using-flexbox-f9d16817f742/
- Card Filter: https://webdesign.tutsplus.com/tutorials/how-to-build-a-filtering-component-in-pure-css--cms-33111
- Youtube stop carousel JS script: https://stackoverflow.com/questions/47079195/youtube-video-iframe-in-a-bootstrap-carousel-stop-carousel-from-sliding-when-v

## 6.2 Content

Content is taken from various pages and press releases on https://littleangeltheatre.com/

## 6.3 Media

Media has all come from Little Angel Theatre.
Background photo of Little Angel's 2018 production of Angelo. Photo by Ellie Kurttz.

## 6.4 Acknowledgements

I received inspiration for this project from Little Angel Theatre, and would like to thank Sophie Waddy for providing resources and a remit.

I would also like to thank Akshat Garg for his support as a mentor and Cormac Lawlor for his support as Code Institute Tutor.
