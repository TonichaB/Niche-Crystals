# Niche-Crystals

Visit the live website [here!](https://tonichab.github.io/Niche-Crystals/)

Niche Crystals is an informative website for users who are interested in the theory of crystal healing and the history of their uses. The website aims to provide a sense of comfort and calm to its users whilst providing an initial introduction to crystal practices. Users are then encouraged to sign up for a newsletter which will give more in depth information every month.
![responsive website example image](assets/images/amiresponsive.webp)

---

## Contents

- [Niche-Crystals](#niche-crystals)
  - [Contents](#contents)
  - [User Experience](#user-experience)
  - [User Stories](#user-stories)
    - [As a user I would like to learn how crystals are used](#as-a-user-i-would-like-to-learn-how-crystals-are-used)
    - [The website should be user friendly on all available devices](#the-website-should-be-user-friendly-on-all-available-devices)
    - [As a user I want additional information on how to introduce new practices and meet like minded people to discuss crystals](#as-a-user-i-want-additional-information-on-how-to-introduce-new-practices-and-meet-like-minded-people-to-discuss-crystals)
- [Design](#design)
  - [Colour Scheme](#colour-scheme)
  - [Typography](#typography)
  - [Imagery](#imagery)
  - [Wireframes](#wireframes)
  - [Search Engine Optimization](#search-engine-optimization)
    - [Home Page](#home-page)
    - [Gallery Page](#gallery-page)
    - [Sign Up Page](#sign-up-page)
    - [Mobile View](#mobile-view)
- [Features](#features)
  - [General Features](#general-features)
    - [Navigation Bar](#navigation-bar)
      - [Desktop View](#desktop-view)
      - [Mobile View](#mobile-view-1)
    - [Landing Page](#landing-page)
    - [Gallery Page](#gallery-page-1)
    - [Sign Up Page](#sign-up-page-1)
    - [Page Footer](#page-footer)
  - [Future Implementations](#future-implementations)
  - [Accessibility](#accessibility)
- [Technologies Used](#technologies-used)
  - [Languages Used](#languages-used)
- [Deployment and Local Development](#deployment-and-local-development)
  - [Deployment](#deployment)
  - [Local Deployment](#local-deployment)
    - [How to Fork](#how-to-fork)
    - [How to Clone](#how-to-clone)
- [Testing](#testing)
  - [Validators](#validators)
    - [CSS Validator](#css-validator)
    - [HTML Validator](#html-validator)
      - [Home Page](#home-page-1)
      - [Gallery Page](#gallery-page-2)
      - [Sign Up Page](#sign-up-page-2)
    - [Lighthouse](#lighthouse)
      - [Home Page](#home-page-2)
      - [Gallery Page](#gallery-page-3)
      - [Sign Up Page](#sign-up-page-3)
  - [Bug Fixes](#bug-fixes)
- [Credits](#credits)
  - [Code Used](#code-used)
  - [Content](#content)
  - [Media](#media)
  - [Acknowledgements](#acknowledgements)
---

## User Experience

The target audience for Niche Crystals is individuals wanting to find more information about the supposed properties of healing crystals and their origin. It is expected the users will be of a beginner level, therefore the site contains simple content to provide an overview of the different uses of crystals and inviting images to provide a positive experience. The Niche Crystals site is intended to encourage users to sign up for a monthly newsletter subscription to find out more about crystals.

## User Stories

### As a user I would like to learn how crystals are used

The homepage of the Niche Crystals site offers an initial overview of the different practices wherein crystals are used, alongside listing individual properties of the more commonly known crystals. Accompanying this the Gallery page offers images of crystals being used in meditation, crystal readings and jewellery to give a pleasing visual of the potential uses of crystals for mindfulness.

### The website should be user friendly on all available devices

Through the use of media queries within the CSS code, the website is adaptable to all screensizes from mobile view to larger desktop screens. The use of Flexbox has allowed for the adjustments of elements on each page ensuring a smooth flow of information in either columns or row formats as applicable. For smaller screen sizes the navigation bar has been adjusted to a dropdown option to create a more user friendly experience and ease of navigation through each page of the site.

### As a user I want additional information on how to introduce new practices and meet like minded people to discuss crystals

The footer of the site includes social media links that are intended to take the user to a group page they can join as an initial pathway to learn more. The final page also includes an easy to complete sign up form for a monthly newsletter containing more information about crystals and upcoming events across the UK. The sign-up form asks the user how they hope crystals can help them to allow for personalisation of the newsletters to ensure future content is user-specific.

---

# Design

## Colour Scheme

![colour scheme image](assets/images/colour-scheme-and-accesibility.webp)
![colour scheme rgb codes](assets/images/colour-scheme-rbg-codes.webp)
The colour scheme has been inspired by crystals in particular amethyst crystals, with the various purple and pink tones making up the majority of the website. These colours are also inspired by the favicon icon for the website to create consistency for the branded image. Text is either in black or white depending on the background for contrast and easier reading for the user. Using the Adobe Color Accessibility Tools the colour scheme is also confirmed to be suitable for colour blind users.

## Typography

The Niche Crystals site contains two fonts, Pontano Sans for the header of each page, and Montserrat for the body of the pages. I have chosen these two font types as they do not contradict one another and create a consistent styling for the website. Both fonts are clear and easy to read to be more accessible for all users. Please see the two fonts shown below;<br>
![pontano sans font image](assets/images/Pontano-Sans-Font.webp)<br>
![montserrat font image](assets/images/Montserrat-font.webp)

## Imagery

The images chosen for the website have been selected due to their high quality on all screen sizes and their relevance for the website. Most images are included within the gallery page, and have been selected to follow consistent stylings and sizes for a sleek appearance on the page. All images used on the website have also been formatted as WEBP documents as these prove to be 25% to 35% smaller than JPEG files resulting in quicker loading times for the user.

## Wireframes

Using Balsamiq during the planning stage of this build I was able to create wireframes for each page and mobile view to use as a guide when building the website.

### Home Page

![wireframe image of homepage](assets/images/Homepage-wireframe.webp)

### Gallery Page

![wireframe image of gallary page](assets/images/gallery-wireframe.webp)

### Sign Up Page

![wireframe image of sign up page](assets/images/sign-up-wireframe.webp)

### Mobile View

![wireframe image of mobile view](assets/images/mobile-wireframe.webp)

## Search Engine Optimization
In order to improve the optimisation of the website's content relevance, and the quality and quantity of website traffic I have included meta tags within the head elements. These tags will create a small description for the website when coming up within the output of a search engine, alongside the addition of keywords to increase the ranking of the website on the search engine's output.

---

# Features

## General Features

### Navigation Bar

Within the head of the page I've included a responsive navbar changing from text in desktop view to a hamburger menu drop-down in mobile view. The navbar shows the current page by underlining the relevant text.

#### Desktop View

![navbar desktop image](assets/images/navbar-desktop.webp)

#### Mobile View

![navbar mobile image](assets/images/navbar-mobile.webp)

### Landing Page

The Landing Page for Niche Crystals opens with a high quality image of crystals with text overlay as a brief introduction to the site. The user can scroll down to view the main content offering information regarding the origins of crystals and their uses. For desktop users, the main content is shown with images and text alongside one another and alternating positions for each text subject. Each subject includes a link to the sign up page encouraging users to sign up for more information.
![landing page image](assets/images/home-page.webp)

### Gallery Page

The Gallery Page of the website provides users with relevant images laid out in a responsive mosaic tile gallery to show the different ways in which crystals can be used. Towards the end of the page, there is also a video showing a crystal being cleansed through the smudging method to give a visual representation on the use of crystals. This page is valuable to the users as it compliments the textual information given on the Landing Page.
![gallery page image](assets/images/gallery-page.webp)

### Sign Up Page

The final page of the website includes a sign-up form allowing the user to sign up for a monthly newsletter, tailored to them, with further information regarding crystal practices and maintenance. The user can specify how they intend to use crystals alongside submitting their full name and email address to then submit the form. At this time there is no backend service connected to the website as this is not currently withint the scope of this project; with this in mind once a user has completed the form a template formdump page provided by Code Institute. If the form is incorrectly completed pop ups will appear to advise the user of the form requirements.
![sign up page image](assets/images/signup-page.webp)

### Page Footer

The footer on eage page includes social media links for Facebook, Instagram, Pinterest and Twitter encouraging the user to stay connected through relative social groups. The links will open in a new tab to allow easy navigation for the user and avoiding any progress on the main website being lost.
![page footer image](assets/images/footer-image.webp)

## Future Implementations

An initial future feature could be further compression or reselection of gallery images to improve the performance levels to be more reliable on devices with varying performance levels. Using the Google Lighthouse Developer Tool I was able to see the webpage performance on the gallery page was less reliable than the other pages on the site.<br>
A broader goal for future implementations would be the inclusion of a Store page allowing the website owner to offer relative products for the user to purchase, such as crystals, jewellery and further reading materials.

## Accessibility

To provide accessibility to the website the following has been incorporated;

- Aria-labels, alt tags and labels have been used for supportive technologies such as screen readers.
- Semantic elements have been used for easy navigation through each page.
- The colour scheme selected is also made suitable for colour-blind users as shown in the design section above.

I have also carried out accessibility checks using the WAVE Chrome Extension which has confirmed no errors. Please see the below results for each page; <br>

### Home Page
![WAVE home page image](assets/images/WAVE-accessibility-homepage.webp)

### Gallery Page
![WAVE gallery page image](assets/images/WAVE-accessibility-gallery.webp)

### Sign Up Page
![Wave sign-up page image](assets/images/WAVE-accessibility-signup.webp)
---

# Technologies Used

The following technologies have been utilised in the production of this website;

- HTML5- The core of the website has been built with HTML5
- CSS- The website styling has been completed using CSS.
- Javascript- In order to utilise the Font Awesome icons a script had to be added using Javascript.
- GitHub- Storage and publishing of the website has been done through GitHub.
- GitHub Pages- The website has been published through GitHub Pages.
- Codeanywhere- This is the IDE used to edit and push changes for the website.
- Font Awesome- Icons such as the social media icons were obtained through the Font Awesome website.
- Favicon Generator Website- I have used this website to generate the favicon code for my chosen image.
- Google Chrome- The majority of the website testing and building has been done with the assistance of Google Chrome and the Developer Tools.
- Pixelied.com Website- I have used this website to convert my images from JPEG/PNG to WEBP.
- Python- Via the terminal in Codeanywhere I have used python3 in order to preview the website using a local HTTP server.
- AmIResponsive Website- To view overall functionality across devices I have used the AmIResponsive website.

## Languages Used

HTML, CSS, Javascript

---

# Deployment and Local Development

## Deployment

The Niche Crystals site has been deployed onto Git Pages.

## Local Deployment

### How to Fork

If you would like to fork the repository:

1. Log in (or sign up) to your account on GitHub.
2. Go to the repository for this project- /TonichaB/Niche-Crystals/
3. Click on the Fork button in the top right corner.

### How to Clone

If you would like to clone this repository:

1. Log in (or sign up) to your account on GitHub.
2. Go to the repository for this project- /TonichaB/Niche-Crystals/
3. Click on the code button, and copy your preferred clone link.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and paste the link copied in step 3 above. Press enter.

---

# Testing

## Validators

### CSS Validator

I have used the [W3C Css Validation Service](https://jigsaw.w3.org/css-validator/validator) to validate the CSS code which has passed with no errors;<br>
![css validation image](assets/images/CSS-validator-pass.webp)

### HTML Validator

I have used the [W3C HTML Checker](https://validator.w3.org/#validate_by_input) to validate the HTML code for each page of the website, all passing with no errors; <br>

#### Home Page

![home page validator image](assets/images/HTML-validator-index.html-pass.webp)

#### Gallery Page

![gallery page validator image](assets/images/HTML-validator-gallery.html-pass.webp)

#### Sign Up Page

![signup page validator image](assets/images/HTML-validator-sign-up.html-pass.webp)

### Lighthouse

I have utilised the Chrome Lighthouse Developer Tool to check the performance of each page of the website. The results are as follows;

#### Home Page

![home page lighthouse image](assets/images/home-page-lighthouse-performance.webp)

#### Gallery Page

![gallery page lighthouse image](assets/images/gallery-lighthouse-performance.webp)

#### Sign Up Page

![signup page lighthouse image](assets/images/signup-lighthouse-performance.webp)

Testing was completed on the following devices to confirm the responsiveness of the site:

- Macbook Pro
- Lenovo Desktop
- Samsung S21 FE mobile
- Ipad Pro

The Niche Crystals site has been tested using the following browsers:

- Google Chrome
- Safari
- Firefox

|       Feature        |                                    Expected Outcome                                     |                     Testing Performed                      |                        Result                         | Pass/Fail |
| :------------------: | :-------------------------------------------------------------------------------------: | :--------------------------------------------------------: | :---------------------------------------------------: | :-------: |
|  **Navigation Bar**  |
|                      |                                                                                         |                                                            |                                                       |           |
| Niche Crystals Title |                  When clicked the user should return to the home page                   |                       Clicked title                        |                Redirected to Home Page                |   Pass    |
|   Hamburger Navbar   |            When selected the navbar should drop down to reveal website pages            |                  Selected Hamburger Icon                   |           Dropdown menu of webpages appears           |   Pass    |
|    Home Page Link    |               When selected the user will be redirected to the home page                |                        Clicked Link                        |                Redirected to Home Page                |   Pass    |
|  Gallery Page Link   |              When selected the user will be redirected to the gallery page              |                        Clicked Link                        |              Redirected to Gallery Page               |   Pass    |
|  Sign Up Page Link   |              When selected the user will be redirected to the sign up page              |                        Clicked Link                        |              Redirected to Sign Up Page               |   Pass    |
|      **Footer**      |
|                      |                                                                                         |                                                            |                                                       |           |
|     Social Icons     |         When clicked a new tab will open for the appropriate social media page          |                       Clicked Icons                        |      New tab opens for each social media website      |   Pass    |
|  **Embedded Video**  |
|                      |                                                                                         |                                                            |                                                       |           |
|    Embedded Video    |                  Video does not autoplay and can be controlled by user                  |                    Clicked play button                     |                      Video plays                      |   Pass    |
|   **Sign Up Page**   |
|                      |                                                                                         |                                                            |                                                       |           |
|     Sign Up Form     | If fields left empty or completed incorrectly a message should notify the user of the error | Clicked submit with form in various stages of completeness | Form requested the sections to be correctly completed |   Pass    |
|     Reset Button     |                    Compeleted form should reset and clear all fields                    |                    Clicked reset button                    |                  Form reset to start                  |   Pass    |

## Bug Fixes

During the process of building the website I came across a couple of bugs to be fixed. The first bug occured when changing the display size of the website to a 4k (2560px x 1856px) view. As shown below, on the home page the cover text has shifted position to lower on the page: <br>
![cover text bug](assets/images/cover-text-bug.webp) <br>
I was able to fix this using a media query for the larger screens in the style.css file, providing the following result: <br>
![cover text solution](assets/images/cover-text-solution.webp) <br>

It also became apparent at one stage that the navigation bar was shifting right when changing to the sign up page. I realised this was a result of the scrollbar not being required for the signup page, dissapearing, and the page shifting to the right to fill space. Using scroll within the body css styling I was able to fix the scrollbar into place on all pages which prevented the navigation bar from moving further.

---

# Credits

## Code Used

When looking for bug solutions I made use of the following;

- As a general guide when completing the readme.md file I have used a [Markdown Guide](https://www.markdownguide.org/cheat-sheet/)
- To fix the movement of the navbar on the sign up page I referred to a [Bootstap Forum](https://forum.bootstrapstudio.io/t/vertical-scroll-bar-moves-fixed-nav-bar-to-left/2309)
- To make the video element more responsive to screen sizes I referred to [Stack Overflow](https://stackoverflow.com/questions/20127763/video-100-width-and-height)
- I found the [Adobe Color](https://color.adobe.com/create/color-accessibility) webpage very useful when determining the best colour scheme.

## Content

- The content has been written using my knowledge of crystals.
- The icons in the footer and within the home page and sign up page were taken from [Font Awesome](https://fontawesome.com/)

## Media

- The images and video implemented throughout the website have been sourced from [Pexels](https://www.pexels.com/). All content used is royalty free.
- To create my favicon icon I used a [Favicon Converter](https://favicon.io/favicon-converter/).

## Acknowledgements

I would like to thank my mentor Luke for his guidance during this project alongside the users of Slack who have built a supportive community and endless source of guidance with each new concept.
