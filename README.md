
![Olivo website logo](/docs/logo_olivo.png)

# Goal for the project

Welcome to [Olivo](<https://capricornog.github.io/Olivo/>) . 

A vibrant online platform that serves as a go-to resource for individuals, aged 30-40, seeking to enhance their culinary experiences and overall well-being through the use of olive oil.

![Olivo website](/docs/olivo_website_screenshot.png)


# Table of Contents
- [Goal for the project](#goal-for-the-project)
- [Table of Contents](#table-of-contents)
- [UX](#ux)
  - [User Goals](#user-goals)
  - [User Stories](#user-stories)
  - [Site Owner Goals](#site-owner-goals)
  - [Requirements](#requirements)
  - [Expectations](#expectations)
- [Design Choices](#design-choices)
  - [Fonts](#fonts)
  - [Icons](#icons)
  - [Colours](#colours)
  - [Structure](#structure)
- [wireframes](#wireframes)
- [Features](#features)
  - [navigation-bar](#navigation-bar)
  - [hero-page](#hero-page)
  - [card-section](#card-section)
  - [benefit-section](#benefit-section)
  - [varieties-section](#varieties-section)
  - [contact-section](#contact-section)
  - [footer](#footer)
- [Features-to-be-added](#features-to-be-added)
- [Technologies-used](#technologies-used)
  - [Languages](#languages)
  - [Libraries \& Framework](#libraries--framework)
  - [Tools](#tools)
- [Testing](#testing)
  - [Feature Testing](#feature-testing)
  - [Browser Compatibility](#browser-compatibility)
  - [Responsiveness](#responsiveness)
  - [Bugs](#bugs)
  - [Code Validation](#code-validation)
  - [Unfixed bugs](#unfixed-bugs)
- [Deployment](#deployment)
- [Credits](#credits)

# UX

## User Goals

* Discover Healthy Recipes.

* Learn About the Benefits of Olive Oil.

* Explore Culinary Inspiration.

## User Stories

* Title: Discovering Healthy Lunch Options

  User Story: As a busy individual in my 30s, I want to find quick and healthy lunch recipes using olive oil that I can incorporate into my daily routine.
   
* Title: Weekend Cooking Adventure

  User Story: As a cooking enthusiast in my 40s, I want to explore unique and adventurous olive oil-based recipes for a special weekend cooking project.
  
* Title: Understanding Olive Oil Varieties

  User Story: As an individual new to cooking with olive oil, I want to learn about different olive oil varieties and their distinct flavors to make informed choices while shopping.

  ## Site Owner Goals

* Promote Olive Oil Consumption.
* Establish Brand Authority (reliable source of information on olive oil).
* Increase User Engagement regularly updating content.

 ## Requirements

* Recipe Database: a comprehensive database of olive oil-based recipes, categorized and searchable by meal type, cuisine, and dietary preferences.
* Clear Recipe Presentation: each recipe should include clear instructions, ingredient lists, nutritional information, and high-quality images to enhance user understanding.
* Responsive Design: ensure the website is mobile-friendly and has a responsive design to accommodate users accessing the site from various devices.
  
 ## Expectations

* Mobile Accessibility: ensure a seamless and enjoyable user experience across various devices, especially on mobile platforms.
* Content Quality: deliver high-quality, well-researched, and visually appealing content.
* Navigation link: proper correct work of all navigation links.
* Submit botton: feedback that the form has been submitted properly.
  
\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Design Choices

## Fonts

I use [Google Font](<https://fonts.google.com/>) to help the selction of fonts.

I will use:

* Montez for logo and heading section.

* Playfair for the Navigation menu and other heading.
  
* Exo for general body.

## Icons

I use [Font Awesome](<https://fontawesome.com/>) for social media links icons or to decorate a section with an icon.

## Colours

I use [Coolors](<https://coolors.co/>) for the selection of the colour scheme, and a classic orange for some over.

*  --light-green: #606C38; 
*   --dark-green: #283618;
*   --rocket-fuel: #FEFAE0;
*   --di-sierra: #DDA15E;
*   --burbon: #BC6C25;
*   hover of text will be orange

![Colour](/docs/colors.png)

* NavBar will have a background light-green
* logo and bottom in it will be di-sierra
* text in other section will be rocket-fuel or burbon 
* hover of icon link will bedark-green


## Structure

I will be building the website in different size for smartphone, tablet, and desktop.
I will be using screen size breakpoint from [Bootstrap](https://getbootstrap.com/).

|Screen Size|Breakpoint|
|:---:|:---:|
|x-small|< 576px|
|small|=> 576px|
|medium|=>768px|
|large|=>992px|

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# wireframes

I used [Balsamiq](<https://balsamiq.com/>) to create my wireframes.

* DESKTOP
  
  ![wireframe_Desktop](/docs/balsamiq.png)

I will use bootstrap to arrange for tablet and mobile and put a screenshot of the webpage underneath.

* TABLET
  
  
* MOBILE

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Features

All the feature, take care of the User Goal and User Stories to realise what has asked.

## navigation-bar
Navigation bar will be responsive for different screen size.

I'll use bootstrap to do so.
 * Desktop
  
   ![Navbar_Desktop](/docs/Navbar_full.png)

   In tablet and mobie bootstrap is used to give a responsive reaction to the bar.

 * Tablet
  
    ![Navbar_Tablet](/docs/Navbar_tablet.png)

 * Mobile
  
    ![Navbar_Mobile](/docs/Navbar_mobile.png)


## hero-page

  The hero page take the first central page in desktop and tablet, adapting it self with bootstrap. 

  I also add a transition backwards.

## card-section

I will have a Meal section, I want to create some cards that will be reponsive on the three format thanks to bootstrap.

* Desktop

  ![Desktop_card](/docs/card_desktop.png)


* Tablet
  
    ![Tablet_card](/docs/tablet_card.png)


* Mobile

    ![Mobile_card](/docs/mobile_card.png)


## benefit-section

The section will be divided in 4  box, two with picture and two with text and background color to create good symmetry, on Desktop and tablet. 

On mobile I will have 3 boxes in line and one image will disapper.
![benefit](/docs/benefit-lg-scr.png)
![benefit-xs](/docs/benefit-xs-scrshoot.png)
![benefit-xs-end](/docs/xs-benefit-scrshoot-end.png)


## varieties-section

This section will use the same principle of boxes of the benefit section, with 6 boxes in line of 3, becoming in line of 2 on mobile.

  ![Varieties](/docs/varieties.png)

  ![Varieties](/docs/varieties_mobile.png)

## contact-section

For this section I get inspired to the Contact page of resume-miniproject-bootstrap4 of [Code Institute](<https://github.com/Code-Institute-Solutions>), readapting and styling to the needs of the website. 

* Desktop

   ![Contact_us-desktop](/docs/contact-us-desktop.png)

* Mobile

  ![Contact_us-mobile](/docs/contact_us-mobile.png)

  After submitting the user get send to [formdump.codeinstitute](<https://formdump.codeinstitute.net/>) page I used to check the form was working properly. 

    ![Contact_us-mobile](/docs/form-codeinstitute.png)

## footer

The footer will be divided in three boxes, will contain text, and icon links. 

Again the design will be responsive and align the boxes.

* Brand
* Contact
* Social with icons
  
  ![Footer](/docs/footer.png)

  ![Footer_mobile](/docs/footer_mobile.png)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Features-to-be-added

* Create a meals or Recipes pages with a library of recipes.
* Possibility to add a recipe as a user.
* Where to buy.
* I would like to add a container with description text inside for the varieties section, the container would appear after hovering or clicking on the images in the varieties section.
* Remove the Codeinstitute formdump and have a feedback of the message been send.

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Technologies-used
  
  ## Languages
* [HTML](https://en.wikipedia.org/wiki/HTML "HTML")
* [CSS](https://en.wikipedia.org/wiki/CSS "CSS")

## Libraries & Framework
* [Google Fonts](https://fonts.google.com/ "Google Fonts")
* [Font Awesome library](https://fontawesome.com/ "Font Awesome")
## Tools
* [Coolors](<https://coolors.co/>)
* [Balsamiq](https://balsamiq.com/wireframes/ "Balsamiq")
* [Bootstrap](https://getbootstrap.com/)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Testing
  ## Feature Testing



|Feature|test|Outcome|
|:---:|:---:|:----:|
|Navbar|Full responsive nvigation bar | User can see Nav bar responsive on different screen and fixed on top of the page ![Navbar_Desktop](/docs/Navbar_full.png) ![Navbar_Desktop](/docs/Navbar_tablet.png)|
|Navbar\Logo| Click on logo| User is brought to the Home page|
|Navbar\Home| Click on Home button|  User is brought to the Home page|
|Navbar\Home| hover Home button|  User see change of color home button ![](/docs/home-scrsh.png) ![home-hover](/docs/home-scrsh-hover.png)|
|Navbar\Meals| Click on Meals button|  User is brought to the Meals section|
|Navbar\Meals| hover Meals button|  User see change of color Meals button|
|Navbar\Why Olive Oil?| Click on Why Olive Oil? button|  User will see a dropdown menu appear ![dropdown button](/docs/whyOO-drop.png)|
|Navbar\Why Olive Oil?| hover Why Olive Oil? button|  User see change of color Why Olive Oil? button|
|Navbar\Why Olive Oil?\Benefit| Click on Benefit button|  User is brought to the Benefit section|
|Navbar\Why Olive Oil?\Benefit| hover Benefit button|  User see change of color Benefit button|
|Navbar\Why Olive Oil?\Varieties| Click on Varieties button|  User is brought to the Varieties section|
|Navbar\Why Olive Oil?\Varieties| hover Varieties button|  User see change of color Varieties button|
|Navbar\Contact| Click on Contact button|  User is brought to the Contact section|
|Navbar\Contact| hover Contact button|  User see change of color Contact button|
|Navbar\Toggle Menu| Visualise toggle menu button resizing the screen|  User will see the button of navigation disappear and appear toggle menu resizing the screen ![Navbar_Desktop](/docs/Navbar_full.png) ![Navbar_Desktop](/docs/Navbar_tablet.png)|
|Navbar\Toggle Menu| Click on toggle menu and hover| User will see appear a dropdown menu and a changing on hover toggle menu, will also see disappear the dropdown menu on clicking again on the toggle button ![Navbar_Desktop](/docs/Navbar_tablet.png) ![toggle-on](/docs/toggle-menu-on.png)|
|Hero img| Visualise hero image properly |User will see an appealing landing page that zoom out to give movement|
|Hero img| Visualise responsive hero image property |User will see different of the hero on different device ![hero](/docs/hero-scr.png) ![hero-xs](/docs/hero-xs-scr.png)|
|Cover text| cover text on different screen| user will see resizing the cover text on different device|
|Meal section| different cards same size in line on desktop, in row of 2 on medium format in row of 1 on small screen| User will see a dispaly of card, rispecting shape, color and font characteristic, responsive on different device, ![meals](/docs/meal-sec-scr.png) ![meal-md](/docs/meal-sec-scr-md.png)![meal-xs](/docs/meal-sec-scr-xs.png) |
| Benefit section| testing responsability of this section| the section will be responsive on different screen size and an image will disappeart on mobile view ![benefit](/docs/benefit-lg-scr.png)![benefit-xs](/docs/benefit-xs-scrshoot.png)![benefit-xs-end](/docs/xs-benefit-scrshoot-end.png) | 
|Varieties section| testing responsive of the section| user will see 6 boxes in row of 3 center in the middle of page going in row of 2 as changing screen size ![varieties-lg](/docs/varietieties-lg.png) ![varieties-md](/docs/varietieties-md.png)  |
|Contact section| testing responviveness| User will see the contact section resize on small screen taking the space available ![contact-lg](/docs/contact-lg.png) ![contact-xs](/docs/contact_us-mobile.png) |
|COntuct us\ Send Recipe| button send recipe will send a message if filled or asked required| user will see different color overing on the button and required filing if not completed form; after compliting the form user will be redirect to Codeinstitute formdump page ![contact-req](/docs/contact-req.png) ![contact-req-hov](/docs/contact-req.png) ![form-codeinstitute](/docs/form-codeinstitute.png)|
|Footer| testing responsiveness footer| User will see different order of footer element on different screen size  ![Footer](/docs/footer.png) ![Footer_mobile](/docs/footer_mobile.png) |
|Footer\ contuct icon| test link icon and hover| User will see the icon link change color and dimension to send to the contact section ![icon-contact](/docs/icon-scr.png)![icon-contact](/docs/icon-scr-hover.png)|
|Footer\ Social icons| test link icon and hover| User will see the icon link change color and dimension to send to website of the link ![social-icon](/docs/social.scr.png)![social-icon-f](/docs/social.scr-f-hover.png)![social-icon-i](/docs/social.scr-i-hover.png)![social-icon-t](/docs/social.scr-t-hover.png)![social-icon-y](/docs/social.scr-y-hover.png)|





   
  ## Browser Compatibility
  | Browser Tested | Intended appearance | intended Responsiveness |
| -------------- | :-----------------: | ----------------------: |
| Chrome         |        Good         |                    Good |
| Opera      |        Good         |                    Good |
| Edge           |        Good         |                    Good |
  ## Responsiveness

  | Device Teste | site responsive <576  |site responsive => 820 |site responsive => 992 | responsive as expected|
| ---:|---:|---:|---:|----:|
| Iphone xr   |   Good   |  N/A |N/A  | Good|
|   Ipad Air   |  N/A   |   Good |N/A |Good |
|    Desktop 1024 px  |   Good |   Good |Good |Good |

  ## Bugs

* During all the Development stage I used [DevTools - Chrome for Developers](<https://developer.chrome.com/docs/devtools>), to allow see how the website was looking on the browser. Then I readapt margin, padding, class name ( considering using Bootstrap ) to what I fell it's most visual apeealing. 

* I noticed that under 768px the cards didn't look so great and too big. FIXING I add col-sm-6 to each div line 86, 96, 106, 117. Then I add a class resize to the div row on line 85 on my index.html, and applied a media queries adding margin left and right and removing padding left and right from container-fluid-meals class under 576 px. the resuld is that the cards take full weight screen only up to 576px, with padding left and right to center them all.
  
* I didn't design a wireframe for smarthpohne or tablet as initially I thought to give the same structure in diffent dimension, I then readapt each section to the screen size.
  
   ![Validator-HTML](/docs/smarphone-landing-screenshot.png)

    ![Validator-HTML](/docs/smatphone-card%20start.png)

    ![Validator-HTML](/docs/smatphone-card-screeshot-end.png)

    ![Validator-HTML](/docs/benefit-xs-scrshoot.png)

    ![Validator-HTML](/docs/xs-benefit-scrshoot-end.png)

    ![Validator-HTML](/docs/varieties-xs-scrshoot.png)

    ![Validator-HTML](/docs/contact-xs-screenshoot.png)

    ![Validator-HTML](/docs/footer-xs-screenshot.png)

* In the varieties section one of the name given as h3 varieties heading was too long causing the images and text to be moved down on xs device, I just change the name to be shorter as a temporary but visually good solution.

* On XS device in the benefit section the two pictures were in colon line, I didn't like to much so I decide to use media queries to make one of the images disapper.

* Another media queries has been used for the cover text id to make the container of different size on xs screen.
  
## Code Validation

* Start to validate the index.html file on [The W3C Markup Validation Service](<https://validator.w3.org/>)  , and have multiple info, Error, or Warning to fix. 
  * INFO line 9 :  Trailing slash on void elements. FIXING removing / simbol.
  * ERROR line 99 : Bad value assets/img/full _aperitivo.jpg for attribute src on element img. FIXING change the name of the img in full-aperitivo.
  * WARNING line 146 : Possible misuse of aria-label. FIXING removing aria-label.
  * WARNING line 170 : Possible misuse of aria-label. FIXING  removing aria-label.
  * ERROR line line 204, 215, 226, 237, 248, 259 : Duplicate ID central-image. FIXING changing all the ID central-image with class:central-image.
  * ERROR line line 205, 216, 227, 238, 249, 260 : Duplicate ID circle-container. FIXING changing all the ID circle-container with class:circle-container.
  * ERRORS line 269 : End tag section seen, but there were open elements. line 196, 197 : Unclosed element div. FIXING I checked the varieties section related to the errors and fixed the position of the element.
  * INFO line 286, 287 : Trailing slash on void elements. FIXING remove / symbol at the end of the tag from line 286, 287.
  * ERRORS line 301 End tag section seen, but there were open elements; line 276 : Unclosed element div. FIXING add closing div /div to line 304 in index.html.
  
    After fixing these errors I got the following message "Document checking completed. No errors or warnings to show." from W3C .

    ![Validator-HTML](/docs/screenshot-validator-html.png)


* Now validate the style.css on [The W3C CSS Validation Service - Jigsaw](<https://jigsaw.w3.org/css-validator/>)

  * ERROR line 317 .varieties-heading	Value Error : margin-bottom only 0 can be a unit. You must put a unit after your number : 1.5. FIXING add rem to 1.5 value.

    After fixing the error I got the following message "Congratulations! No Error Found." from W3C . There are some warnings needed to be fixed related to the browser transiction.
  
    ![Validator-CSS](/docs/screenshot-css-validator.png)


## Unfixed bugs

The hero image under 992px as a margin on the right, the page scroll on the right and there is this margin of a few pixel that considering the deadline of the project I can't fix at the moment.

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Deployment

Following writing the code then commiting and pushing to GitHub, this project was deployed using GitHub by the following steps.

* Navigate to the repository on github and click 'Settings'.
Then select 'Pages' on the side navigation.
* Select the 'None' dropdown, and then click 'master'.
* Click on the 'Save' button.
* Now the website is now live on https://capricornog.github.io/Olivo/
* If any changes are required, they can be done, commited and pushed to GitHub and the changes will be updated.




\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Credits

For the lessons, the support and ispiration of the website I have to thanks,

* [Code Institute](<https://codeinstitute.net/full-stack-software-development-diploma/?utm_term=code%20institute&utm_campaign=CI+-+UK+-+Search+-+Brand&utm_source=adwords&utm_medium=ppc&hsa_acc=8983321581&hsa_cam=1578649861&hsa_grp=62188641240&hsa_ad=635720257674&hsa_src=g&hsa_tgt=kwd-319867646331&hsa_kw=code%20institute&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gad_source=1&gclid=Cj0KCQiA2eKtBhDcARIsAEGTG41JrbhjWx9ubvxp5AhBL9ygCNkZjvc-HuC8gEckzkhyMbkLS9SXCloaAh4QEALw_wcB>)

For adjustment, help and advice,

* [Simen Daehlin](https://github.com/Eventyret "Simen Daehlin") my mentor for the project.

A lot of ideas came trought resume-miniproject-bootstrap4 of [Code Institute](<https://github.com/Code-Institute-Solutions>)

For the colours [Coolors](<https://coolors.co/>)

For the images [Pexel](https://www.pexels.com/)

For the responsive image of the website [Am I Responsive? - ui.dev](https://ui.dev/amiresponsive)




\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;
