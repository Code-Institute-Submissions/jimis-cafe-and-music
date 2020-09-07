# Manual Testing

## Functionality

### Links and buttons

| Component | Intended Function | Works as Intended? | Fix |
| -------------- | ------------------- | ---------------- | --- |
|**Home link**  on expanded navbar |Takes user to top of page | Yes | N/A |
|**Cafe link**  on expanded navbar |Takes user to Cafe section of page | Yes | N/A |
|**Vinyl link**  on expanded navbar |Takes user to Vinyl section of page | Yes | N/A |
|**Live Music link**  on expanded navbar |Takes user to Live Music section of page | Yes | N/A |
|**Your Visit link**  on expanded navbar |Takes user to Your Visit section of page | Yes | N/A |
|**Navbar toggle** button on collapsed navbar |Opens vertical nav dropdown menu | Yes | N/A |
|**Home link** on collapsed navbar |Takes user to top of page | Yes | N/A |
|**Cafe link**  on collapsed navbar |Takes user to Cafe section of page | Yes | N/A |
|**Vinyl link**  on collapsed navbar |Takes user to Vinyl section of page | Yes | N/A |
|**Live Music link** on collapsed navbar |Takes user to Live Music section of page | Yes | N/A |
|**Your Visit link** on collapsed navbar |Takes user to Your Visit section of page | Yes | N/A |
|Bootstrap carousel **next** button |Transitions to next slide | Yes | N/A |
|Bootstrap carousel **previous** button |Transitions to previous slide | Yes | N/A |
|Bootstrap carousel indicator **1** |Transitions from any slide to slide 1 | Yes | N/A |
|Bootstrap carousel indicator **2** |Transitions from any slide to slide 2 | Yes | N/A |
|Bootstrap carousel indicator **3** |Transitions from any slide to slide 3 | Yes | N/A |
|Bootstrap carousel indicator **4** |Transitions from any slide to slide 4 | Yes | N/A |
|**your visit button** on carousel slide 1 |Takes user to Your Visit section of page | Yes | N/A |
|**our cafe button** on carousel slide 2 |Takes user to Cafe section of page | Yes | N/A |
|**our vinyl button** on carousel slide 3 |Takes user to Vinyl section of page | Yes | N/A |
|**our live music button** on carousel slide 4 |Takes user to Live Music section of page | Yes | N/A |
|**see our menu button** in the Cafe section |Opens the PDF of the cafe menu in a new tab | Yes | N/A |
|**Email link** in Your Visit section |Opens the user's default mail application and begins an email to info@jimiscafeandmusic | Yes | N/A |
|**Telephone link** in Your Visit section (web) |Open's the user's phone application, ready to call the number | Yes | N/A |
|**Telephone link** in Your Visit section (mobile) |Gives the user the option to call the number from their mobile | Yes | N/A |
|**Facebook link icon** in the footer (web) |Takes user to the Facebook homepage in a new tab | Yes | N/A |
|**Facebook link icon** in the footer (mobile) |Takes user to the Facebook app, or facebook homepage | Yes | N/A |
|**Instagram link icon** in the footer (web) |Takes user to the Instagram homepage in a new tab | Yes | N/A |
|**Instagram link icon** in the footer (mobile) |Takes user to the Instagram app, or Instagram homepage | Yes | N/A |
|**Youtube link icon** in the footer (web) |Takes user to the Youtube homepage in a new tab | Yes | N/A |
|**Youtube link icon** in the footer (mobile) |Takes user to the Youtube app, or Youtube homepage | Yes | N/A |

<h3>Hover/Focus effects</h3>

| Component | Intended Function | Works as Intended? | Fix |
| -------------- | ------------------- | ---------------- | --- |
|Links on expanded navigation |Transitions to red when the user hovers cursor | Yes | N/A |
|Links on expanded navigation |Transitions to red when the user presses TAB to focus them | Yes | N/A |
|Links on collapsed navigation |Transitions to red when the user hovers cursor | Yes | N/A |
|Links on collapsed navigation |Transitions to red when the user presses TAB to focus them | Yes | N/A |
|Buttons on carousel |Growing in size and text colour change transition when user hovers cursor | Yes | N/A |
|Buttons on carousel |Growing in size and text colour change when user presses TAB to focus them | Yes | N/A |
|**see our menu button** in Cafe section |Growing in size and text colour change transition when user hovers cursor | Yes | N/A |
|**see our menu button** in Cafe section |Growing in size and text colour change when user presses TAB to focus them | Yes | N/A |
|Social icons in the footer |Transitions to red when the user hovers cursor | Yes | N/A |
|Social icons in the footer |Transitions to red when user presses TAB to focus them | Yes | N/A |

<h3>Animations</h3>

| Component | Intended Result | Works as intended? | Fix |
| -------------- | ------------------- | ---------------- | --- |
|Carousel captions |The text, button and background fade in straight after the carousel slide moves in | Yes | N/A |

## Usability

I carried out usability tests based on the needs of the users in my user stories. 

### User goal #1 

> As a user, I want the website to give me a feel for the venue and convince me to visit by eliciting an emotional response through powerful and compelling content.

The user sees the venue branding straight away, both on desktop and mobile, and is welcomed with the venue's 'elevator pitch' on the carousel. The colourful graffiti photo of Jimi Hendrix is bold, eye-catching and relevant the theme of the venue.

!["What the user first sees when accessing the site."](https://github.com/tobyjbrown/jimis-cafe-and-music/blob/master/assets/images/write-up/user-story-1-1.png)

Information is then progressively disclosed in manageable portions through the carousel and clear buttons are presented for the user to learn more about the features they are interested in. Otherwise, the user can scroll down to the "gallery" portion of the site to see fictitious photographs of the venue that allow the user to become excited about visiting.

!["As the user progresses down to see photographs."](https://github.com/tobyjbrown/jimis-cafe-and-music/blob/master/assets/images/write-up/user-story-1-2.png)

The simple colour scheme of the site and the use of empty space allows for the content to take center stage and have a greater impact in each section. 

!["The user scrolls through the text-based content of the page."](https://github.com/tobyjbrown/jimis-cafe-and-music/blob/master/assets/images/write-up/user-story-1-3.gif)

### User goal #2

> As a user, I want to be able to easily find information I require for my visit, such as opening times, contact details, live music information and cafe menu items.

The main navigation of the site is always available to the user, either through the 'burger' navbar button or stuck to the top of the viewport on large screens. Therefore, the user can always navigate to the information they require. The navigation links take the user to the section of interest clearly described in the link itself and users are therefore not met with information they did not require/expect. The section headings in the site make it clear to the user where they currently are and the ordering of the links in the navbar reflect the order of sections on the page.

!["A user visits the site looking for contact details."](https://github.com/tobyjbrown/jimis-cafe-and-music/blob/master/assets/images/write-up/user-story-2.gif)

## Responsiveness

To test the responsiveness of the site, I used the Google Chrome Developer Tools on the 'Responsive' setting to test in a content-driven rather than device-driven way. For the below tests I gradually resized the window from 2800px wide to 250px.

| Component | Intended Result | Works as intended? | Fix |
| --------- | --------------- | ------------------ | --- |
| Text | Should be clear, visible and readable at all screen sizes | Yes | N/A |
| Images | Should maintain ratio and not appear distorted or pixelated | Yes | N/A |
| Layout | Information should maintain logical hierarchy and elements should not become overcrouded or ovelap | Yes | N/A |
| Functionality | Buttons, links and clickable icons should remain clickable | Yes | N/A |

<h2>Cloud version testing</h2>

After carrying out the same testing outlined above on the cloud-hosted version of the site (Github pages), the site works as expected without any problems.