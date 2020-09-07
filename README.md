# [Jimi's: Cafe, Vinyl and Live Music](https://tobyjbrown.github.io/jimis-cafe-and-music/)

!["The project website tested on various devices"](https://github.com/tobyjbrown/jimis-cafe-and-music/blob/master/assets/images/write-up/jimis-devices-mockup.png)

---

## Table of Contents

- [Project Overview](#Project-Overview)
- [UX](#UX)
    * [Strategy](#Strategy)
        * [Business Objectives](#Business-Objectives)
        * [User Stories](#User-Stories)
    * [Scope/Features](#Scope/Features)
        * [Current Features](#Current-Features)
        * [Future Features](#Future-Features)
        * [Ongoing Features](#Ongoing-Features)
    * [Structure](#Structure)
    * [Skeleton](#Skeleton)
    * [Surface](#Surface)
        * [Colour](#Colour)
        * [Typography](#Typography)
- [Technologies and Libraries](#Technologies-and-Libraries)
- [Resources and Tools](#Resources-and-Tools)
- [Testing](#Testing)
    * [Validation](#Validation)
    * [Manual Testing](#Manual-Testing)
- [Deployment](#Deployment)
- [Credits](#Credits)

---

## Project Overview

Jimi's is a website for a fictitious blues-themed cafe, record shop and live music venue. The website would be used to provide new/returning customers with essential information about the venue, such as contact information, opening times, etc., and to pursuade potential customers to visit.

## UX

### Strategy

#### Business Objectives
- To increase sales and footfall at the venue.
- To persuade potential visitors to visit and spend money.
- To provide decided visitors with the key information requred for their visit.

#### User Stories
> As a user, I want the website to give me a feel for the venue and convince me to visit by eliciting an emotional response through powerful and compelling content.

> As a user, I want to be able to easily find information I require for my visit, such as opening times, contact details, live music information and cafe menu items.

### Scope/Features

#### Current Features
- Core Jimi's branding (logo and tagline)
- Expanded/collapsed navigation visible at all times
- Emotionally compelling text and photo content to reinforce brand
- Key contact information that is expected of cafe/restaurants
- Cafe food menu
- Social links for users to recieve updates on other platforms
- Linear information structure
	
#### Future Features
- The current sections expanded in more detail to seperate pages, taking the user away from the linear structure
- A dedicated 'Gallery' page to include up-to-date photos/videos of live performances at the venue
- A curated blog section to document the collection of vinyl records that the store is famous for
- A 'scrollspy' feature which highlights the current section being viewed in the navbar to reinforce the user's location on the page
- Smooth scrolling to work in all broswers

#### Ongoing Features
- Changes to the live music listings and the cafe menu to be kept up-to-date

### Structure

The site presents information in a linear fashion, with all information available on a single scrolling page. This is suitable for a 'minimum viable product' website that serves the user's most basic needs with room to scale up in future implementations. Key pieces of information such as opening times, contact details, etc., are placed at the bottom of the page in a dedicated contact section (called "your visit" on the Jimi's website) to conform to user expectations and standard practices.

### Skeleton

I used [Balsamiq](https://balsamiq.com) to create 3 wireframes for the site, planning the general layout of content at small, medium and large screens.

- [Small screens](https://github.com/tobyjbrown/jimis-cafe-and-music/blob/master/assets/images/write-up/index-wireframe-small.png)
- [Medium screens](https://github.com/tobyjbrown/jimis-cafe-and-music/blob/master/assets/images/write-up/index-wireframe-medium.png)
- [Large screens](https://github.com/tobyjbrown/jimis-cafe-and-music/blob/master/assets/images/write-up/index-wireframe-large.png)

The site's layout aims to create the 'progressive disclosure' effect with its content. The carousel gives a taste of each individual section and allows the user to jump to the section they are interested in via the button on the slide. Alternatively, the user can scroll down to see photographs of the fictitious venue in action which aim to draw the user's attention in a 'show, don't tell' fashion. The text-based sections of the site appear in the order that they are referenced in the site logo and navbar. The navigation remains at the top of the page and is accessible to the user at all times in order to allow for fast retrieval of information. 

### Surface

#### Colour

- ![#f03c15](https://via.placeholder.com/15/d44337/000000?text=+) `#d44337`
- ![#c5f015](https://via.placeholder.com/15/f3bd45/000000?text=+) `#f3bd45`
- ![#1589F0](https://via.placeholder.com/15/914d00/000000?text=+) `#914d00`

The site uses a simple, analogous combination of colours which follows the fictitious company's branding and allows for the content to be the main focus. Whitespace is used heavily to add emphasis to the areas which do use colour, and place further importance on the content of the site. The footer utilises a combination of greys which sets its content apart from the site's main content.

### Typography

[Denk One](https://fonts.google.com/specimen/Denk+One) - used for `h1`, `h2`, `nav li` and `.btn` elements.

I decided to use 'Denk One' for the main logo text, section headings, navigation links and buttons of the site. When experimenting with fonts, I was looking for something that was bold and consistent in uppercase but also had plenty of character and I liked 'Denk One' as soon as I tried it out.

[Open Sans](https://fonts.google.com/specimen/Open+Sans) - used for `.site-title-tagline` element.

The tagline below the title on large screens which reads "Cafe • Vinyl • Live Music" uses 'Open Sans', a clean sans-serif font that adds a modern influence to the venue logo. 

[Merriweather](https://fonts.google.com/specimen/Merriweather) - used for `h3` and `p` elements.

For the main body and `h3` elements of the site I used 'Merriweather', a highly readable serif font that I believe provides a nice contrast to the more decorative 'Denk One' headings.

## Technologies and Libraries

1. !["HTML5 Badge"](https://img.shields.io/badge/HTML-5-E34F26?logo=html5)
- [HTML5](https://www.w3.org/TR/html52/introduction.html#introduction) - A markup language used to structure and present the content on the site.
2. !["CSS Badge"](https://img.shields.io/badge/CSS-3-1572B6?logo=css3)
- [CSS](https://www.w3.org/standards/webdesign/htmlcss) - Used to create stylesheets that describe the presentation of the content on the site.
3. !["Bootstrap Badge"](https://img.shields.io/badge/Bootstrap-4-563D7C?logo=bootstrap)
- [Bootstrap](https://getbootstrap.com) - A CSS framework, used for the collapsing navigation and carousel.
4. !["Animate.css Badge](https://img.shields.io/badge/Animate.css-orange)
- [Animate.css](https://animate.style) - A CSS library, used for the fading in of content on the carousel.
5. !["Fontawesome Badge"](https://img.shields.io/badge/Font_Awesome-5.14-339AF0?logo=font-awesome)
- [Font Awesome](https://fontawesome.com) - A CSS library, used for the icons in the Cafe section and social media icons in the footer.
6. !["Git Badge"](https://img.shields.io/badge/Git-000?logo=git)
- [Git](https://git-scm.com) - A version control system used to keep track of changes made to the source code.
7. !["Github Badge"](https://img.shields.io/badge/Github-000?logo=github)
- [Github](https://github.com) - A remote code hosting platform, used during development to share with my tutor and deploy my project through [Github Pages](https://pages.github.com).

## Resources and Tools

- [shutterstock.com](https://www.shutterstock.com/home) - Used to source the stock photos for the carousel and Gallery section in addition to the SVG Cafe menu template.
- [dreamstime.com](https://www.dreamstime.com) - Used to source the graffiti photograph of Jimi Hendrix to be used in the carousel.
- [placeit.net](https://placeit.net) - Used to create the street sign mockup of Jimi's which is shown in the Gallery section of the site.
- [ami.responsivdesign.is](http://ami.responsivedesign.is) - Used to create the mockup of my site on various devices for the beginning of this README.md file.
- [W3C HTML Validation Service](https://validator.w3.org) - Used to validate my HTML code in the testing process.
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) - Used to validate my CSS code in the testing process.
- [GIMP](https://www.gimp.org) - Used to edit and reduce the filesizes of the site's images.
- [Inkscape](https://inkscape.org) - Used to create the site's main logo and tagline PNG (which was swapped for HTML/CSS during the development process, but can be seen at the top of this readme) and for editing the stock SVG Cafe menu template.
- [Balsamiq](https://balsamiq.com) - Used to create the wireframes during the Skeleton phase of UX design.
- [VS Code](https://code.visualstudio.com) - My IDE of choice, used with [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for instant feedback during development.
- [Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools) - For testing the responsiveness of my site and used to find the breakpoints for my media queries.
- [Writed](http://writed.io) - For keeping notes and drafting text-based content throughout the development of my project. 

## Testing

I developed the site using [VS Code](https://code.visualstudio.com) with the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) plugin, which allowed for instant feedback and testing to inform my development process. 

### Validation

When I first validated my HTML code with the [HTML Validation Service](https://validator.w3.org), there was an unclosed tag in my bootstrap carousel and therefore an error was flagged by the validator. After quickly fixing this, the HTML passed the validator with no issues.

My CSS passed the [CSS Validation Service](https://jigsaw.w3.org/css-validator/) without any issues.

### Manual testing

I carried out testing on the finished development version of my site through Google chrome and VS Code Live Server. I then repeated in multiple browsers before testing the cloud version hosted on Github pages. Click [here](https://github.com/tobyjbrown/jimis-cafe-and-music/blob/master/assets/images/write-up/testing.md) for a report of the manual testing process which tested functionality, usability (aligned with user stories) and responsiveness.

## Deployment

I deployed my site through GitHub pages. The steps I took were as follows:

1. Created a local repository on my machine which included the site files, assets and an empty README.md file.
2. Used `git init` in the terminal to initialise git in the repository.
3. Staged and commited all the files in the local repository with the message `"Initial commit"`.
4. Created a repository on Github with a name and description, leaving the "Initialise with README" checkbox unselected.
5. Copied the code on the next page and pasted it into the terminal, pushing the local repository to Github.
6. In the settings tab on the Github repository, I scrolled down to GitHub Pages, clicked on the master branch and recieved a [live URL](https://github.com/tobyjbrown/jimis-cafe-and-music/blob/master/assets/images/write-up/logo-main.png) for the site.

## Credits

- [CSS Tricks](https://css-tricks.com) for help with the CSS `auto-fit` property for my Gallery grid and the CSS `object-position` property for one of the images in my Gallery. 
- [Kevin Powell](https://www.kevinpowell.co) for his amazing CSS layout tips.
- [Should I Prefix](http://shouldiprefix.com) for helping me find which CSS properties required browser prefixes.
- [A11Y Project](https://www.a11yproject.com) for providing guidelines for accessibiliy.
- [Font Awesome](https://fontawesome.com/how-to-use/on-the-web/other-topics/accessibility) for providing screen reader guidelines for use with their icons.
- My tutor Adegbenga Adeye for his great help and guidance throughout the project.