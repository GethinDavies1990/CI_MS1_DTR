# Duck's Tap room

Developed by Gethin Davies

![Mock up](docs/mock.jpg)

Duck's Tap room is a craft brewery aimed at people in the craft beer scene. Each week the brewery makes exciting new flavours and experiments these exciting new creation's with their punters. Duck's tap room's website will be useful to find the opening times of the establishment and also to get in touch to book a table. It also showcases the week's events the Tap room has scheduled.

[Live Website](https://gethindavies1990.github.io/CI_MS1_DTR/)


## Table of Content

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requirements and Expectations](#user-requirements-and-expectations)
    3. [User Stories](#user-stories)
3. [Design](#design)
    1. [Design Choices](#design-choices)
    2. [Color](#colours)
    3. [Fonts](#fonts)
    4. [Structure](#structure)
    5. [Wireframes](#wireframes)
4. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks & Tools](#frameworks-&-tools)
5. [Features](#features)
6. [Testing](#validation)
    1. [HTML Validation](#HTML-validation)
    2. [CSS Validation](#CSS-validation)
    3. [Accessibility](#accessibility)
    4. [Performance](#performance)
    5. [Device testing](#performing-tests-on-various-devices)
    6. [Browser compatibility](#browser-compatability)
    7. [Testing user stories](#testing-user-stories)
8. [Bugs](#Bugs)
9. [Deployment](#deployment)
10. [Credits](#credits)
11. [Acknowledgements](#acknowledgements)

## Project Goals 

### User Goals
- Finding bar/pub/tap room that offers craft beers
- Find the upcoming weeks events
- Find information on the taproom
- Find the location of the tap room

### Site Owner Goals
- Increase in visitors to the taproom
- Promote the business
- Provide a way for new and existing customers to contact the business.
- Provide essential information about the business to customers.
- Provide the customer with a details related to the events taking place at the taproom

## User Experience

### Target Audience
- People looking for a place to enjoy craft beers and great atmosphere
- People looking for a place to meet with friends

### User Requirements and Expectations

- A simple and intuitive navigation system
- Quickly and easily find relevant information
- Links and functions that work as expected
- Good presentation and a visually appealing design regardless of screen size
- An easy way to contact the business
- Simple content that the user can skim read
- Accessibility

### User Stories

#### First-time User 
1. As a first time user, I want to know where the tap room is located
2. As a first time user, I want to know how to get in contact with the tap room
3. As a first time user, I want to know more about about the taproom
4. As a first time user, I want to find out what events they have on

#### Returning User
5. As a returning user, I want to find a phone number to call to book a table
6. As a returning user, I want to what events they have on
7. As a returning user, I want know what the brew of the week is
8. As a returning user, I want to find the tap room social handles
9. As a returning user, I want to get directions to the tap room

#### Site Owner 
10. As the site owner, I want users to find info about upcoming events
11. As the site owner, I want users to get to know the tap room
12. As the site owner, I want the users to be able to contact us
13. As the site owner, I want the users to know what the brew of the week is

## Design

### Design Choices
The webpage was designed to be easy to navigate and eye catching with a nice contrast of colors to appeal to the customer, it was made to be fully responsive on all devices. 

### Colour
The color scheme chosen was to reflect the tap rooms mascot duck, with a nice bright shade of green and bright yellow. Which is both present on the mascot. I went for the 60%–30%–10% color scheme, (60%-yellow, 30%-charcoal, 10%-green) I mainly chose the color of yellow to be present for the main pages of the website and the dark charcoal was used in the navigation bar and the footer of the website. I used the green color in little instances so they really pop in certain areas we ma want to draw the user to.
<br>

![Colour scheme](docs/features/color-pallete.png)


### Fonts
Montserrat was used mainly for the headings within the website.
<br>
Source Sans Pro was used for the mostly the p elements in the website

### Logo

I found the logo of the duck online, and removed some parts which wasn't needed to make the logo 2 dimensional, I altered the colors to myself to match the tap rooms color pallette. the text on the logo was made by me using adobe illustrator.

![logo](docs/features/ducks-brew-ver.1.webp)

### Structure

The page is structured to be user friendly and only had two pages the index page and the book a table page.
The website consists of 2 separate pages with a total of 6 sections: 
- The index page includes a hero section with a CTA(call to action) for the user to book a table
- A Testimonial section so new users can see past experiences from other users while visiting the tap room.
- The our story section which details the birth of the tap room and its growth in recent years and how it became what it is.
- An event section so the user can see what events take place on the given week.
- A how to find us section which includes the business's address, google map and contact form information.
- The book a table page, which includes a form the user can submit to reserve their space

### Wireframes

<details><summary>Hero</summary>
<img src="docs/wireframes/wf-hero.jpg">
</details>
<details><summary>Testimonial</summary>
<img src="docs/wireframes/wf-testimonial.jpg">
</details>
<details><summary>Our Story</summary>
<img src="docs/wireframes/wf-our-story.jpg">
</details>
<details><summary>Contact</summary>
<img src="docs/wireframes/wf-contact.jpg">
</details>
<details><summary>Footer</summary>
<img src="docs/wireframes/wf-footer.jpg">
</details>

## Technologies Used

### Languages
- HTML
- CSS

### Frameworks & Tools
- Bootstrap v5.2.1
- Git
- GitHub
- Gitpod
- Adobe Illustrator
- Balsamiq
- Google Fonts
- Font Awsome
- Favicon<span>.</span>io

## Features
The page consists of 2 pages and fourteen features

## Navigation Bar
- Featured on all two pages
- The navbar is fully responsive and changes to a toggler (hamburger menu) on smaller screens and includes
links to the Homepage, our story, Events, how to find us section using the ID tags, the book table link takes you to a separate page. The Navigation page is fixed to the top to always be present on scroll so if the user wants to navigate quickly to a different section they can do so. 
- It allows users to easily navigate the page
- The link for the page the user is currently on is highlighted in white, when the user scrolls over the other links the text will change color to highlight it is a clickable element.

![Nav Bar](docs/features/nav.jpg)

### hero
- Introduces the user to the tap room with a image showcasing a business that has great atmosphere
- Includes a CTA (Call to action) button for the user to book a table

![Hero Section](docs/features/hero.jpg)

### Testimonials
- The user instantly see's some customer testimonials of recent visits.

![Testimonial](docs/features/testimonial.jpg)

### Our Story
- Allowes users to see how the tap room was established and the growth it has undertaken up to the current year

![Our Story](docs/features/our-story.jpg)

### Events
- The events section was made using a grid system, each grid square offers a new event for that week.

![Events](docs/features/events.jpg)

### How to find us
- Gives the user a contact box to submit a inquiry
- The user is also able to see the google map of the business
- The user can get access to the contact information
- The user can find out the telephone number and email address 

![How to Find us](docs/features/how-to-find-us.jpg)

### Book a Table
- user is able to submit a from to reserve a space at he taproom

![Reviews](docs/features/book-table.jpg)

### Meet the Chef
- Features a short bio of the chef with an image of the chef on the left side
- User stories covered: 11

![Meet the Chef](docs/features/feature-meet-the-chef.jpg)

### Menu 
- Gives an overview of the menu in five sections: starters, main meals, kids meals, dessers, and wine.
- Each section of the menu is accompanied with an image of one of the items form the menu
- Features pricing
- User stories covered: 2, 8

![Menu](docs/features/feature-menu.jpg)

### Image Gallery
- Imagery of the restaurant arranged in a grid
- User stories covered: 4

![Gallery](docs/features/feature-gallery.jpg)

### Promo Video
- A YouTube video to promote the restaurant 
- User stories covered: 4

![Video](docs/features/feature-video.jpg)

### Contact Form
- A way for user to provide feedback
- User stories covered: 9, 15

![Contact Form](docs/features/feature-contact-form.jpg)

### Map
- Shows the restaurant location on an embeded Google Map
- User stories covered: 1, 12

![Map](docs/features/feature-map.jpg)

### Info Box
- Provides the user with information about the restaurant including addres, phone number, email, and the name of the owner
- User stories covered: 7, 15

![Info Box](docs/features/feature-info-box.jpg)

## Validation

### HTML Validation
The W3C Markup Validation Service was used to validate the HTML of the website. All pages pass with no errors no warnings to show.
<details><summary>Home</summary>
<img src="docs/validation/validation-html-index.jpg">
</details>
<details><summary>About</summary>
<img src="docs/validation/validation-html-about.jpg">
</details>
<details><summary>Menu</summary>
<img src="docs/validation/validation-html-menu.jpg">
</details>
<details><summary>Gallery</summary>
<img src="docs/validation/validation-html-gallery.jpg">
</details>
<details><summary>Home</summary>
<img src="docs/validation/validation-html-contact.jpg">
</details>

### CSS Validation
The W3C Jigsaw CSS Validation Service was used to validate the CSS of the website.
When validating the page as a whole, the validator shows some errors linked to Bootstrap v5.0. When validating just my own custom CSS it passes with no errors found and some warnings associated to using root variables.
<details><summary>whole page</summary>
<img src="docs/validation/validation-css-whole-page.jpg">
</details>
<details><summary>style.css</summary>
<img src="docs/validation/validation-css-style.jpg">
</details>

### Accessibility
The WAVE WebAIM web accessibility evaluation tool was used to ensure the website met high accessibility standards. All pages pass with 0 errors.
<details><summary>Home</summary>
<img src="docs/validation/validation-accessibility-index.jpg">
</details>
<details><summary>About</summary>
<img src="docs/validation/validation-accessibility-about.jpg">
</details>
<details><summary>Menu</summary>
<img src="docs/validation/validation-accessibility-menu.jpg">
</details>
<details><summary>Gallery</summary>
<img src="docs/validation/validation-accessibility-gallery.jpg">
</details>
<details><summary>Contact</summary>
<img src="docs/validation/validation-accessibility-contact.jpg">
</details>

### Performance 
Google Lighthouse in Google Chrome Developer Tools was used to test the performance of the website. 

<details><summary>Home</summary>
<img src="docs/validation/lighthouse-performance-index.jpg">
</details>
<details><summary>About</summary>
<img src="docs/validation/lighthouse-performance-about.jpg">
</details>
<details><summary>Menu</summary>
<img src="docs/validation/lighthouse-performance-menu.jpg">
</details>
<details><summary>Gallery</summary>
<img src="docs/validation/lighthouse-performance-gallery.jpg">
</details>
<details><summary>Contact</summary>
<img src="docs/validation/lighthouse-performance-contact.jpg">
</details>

### Performing tests on various devices 
The website was tested on the following devices:
- Lenovo Yoga 2 Pro (both in pc and tablet mode)
- Honor 20 pro
- Xiaomi Redmi Note 7

In addition, the website was tested using Google Chrome Developer Tools Device Toggeling option for all available device options.

### Browser compatability
The website was tested on the following browsers:
- Google Chrome
- Mozilla Firefox
- Microsoft Egde

### Testing user stories

1. As a first time user, I want to know where the restaurant is lokated

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Map | Navigate to the Contact Us page, locate the Google Map | Locating a map showing the location of the restaurant | Works as expected |
| Footer - contact information section | On any page scroll down to the footer | Find the address of the restaurant | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-1v1-12.jpg">
<img src="docs/user-story-testing/user-story-1v2.jpg">
</details>

2. As a first time user, I want to know the price range

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Menu | Navigate to the Menu page | See prices on menu page | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-2.jpg">
</details>

3. As a first time user, I want to know more about the restaurant

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| About Us | Navigate to the About page and locate the About Us section | Find description of the restaurant | Works as expected |
| Customer reviews | Navigate to the About page, scroll down to What our guests say section | Read customer reviews | Works as expected | 

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-3-14.jpg">
</details>

4. As a first time user, I want to get a feel of what to expect at the restaurant

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Gallery | Navigate to the Gallery page | Find pictures of the restaurant and food served there | Works as expected |
| Promo video | Navigate to the GAlelry page and scroll to the promo video | Watch promo video | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-4.jpg">
</details>

5. As a returning user, I want to see the Sunday meal offer

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Meal-deal | On home page scroll down to the Sunday meal deal section | Find the meal-deal for the upcomming Sunday | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-5.jpg">
</details>

6. As a returnign user, I want to know the opening times

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Footer - opening times section | On any page scroll to the footer | See opening times | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-6.jpg">
</details>

7. As a returning user, I want to find a phone number to call for reservation

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Footer - contact information section | On any page scroll to the footer | See phone number | Works as expected |
| Info Box | Navigate to Contact Us page and locate the How to find us section | See phone number | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-7v1-15.jpg">
<img src="docs/user-story-testing/user-story-7v2-15.jpg">
</details>

8. As a returning user, I want to see the menu

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Menu | Navigate to the menu page | Read the menu | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-8.jpg">
</details>

9. As a returning user, I want to leave some comment, suggestion or message to the staff

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact Form | Navigate to the Contact Us Page and locate the contact form, fill out and submit contact form | Data submited via contact form | Works as expectd |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-9-15.jpg">
</details>

10. As a returning user, I want to find the restaurant on social media

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Footer - social media section | On any page scroll to the bottom | Click on social media links | Works as expected | 

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-10.jpg">
</details>

11. As a returning user, I want to know who is preparing the food

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Meet the Chef | Navigate to the About page and scroll down to Meet the Chef section | Find brief bio of the Chef | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-11.jpg">
</details>

12. As a returning user, I want to get directions to the restaurant

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Map | Navigate to the Contact Us page, locate the map and click on directions link | See directions to the restaurant on Goole Maps | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-1v1-12.jpg">
</details>

13. As the site owner, I want users to find news about upcoming events or changes in opening times

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| News | Scroll down on home page and locate news section | Find latest news | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-13.jpg">
</details>

14. As the site owner, I want users to get to know the restaurant 

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| About Us | Navigate to About page and locate About Us section | See relevant information about the restaurant | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-3-14.jpg">
</details>

15. As the site owner, I want the users to be able to contact us

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact Form | Navigate to the Contact Us Page and locate the contact form, fill out and submit contact form | Data submited via contact form | Works as expectd |
| Info Box | Navigate to Contact Us page and locate the How to find us section | Find the phone number | Works as expected |
| Footer - contact information section | On any page scroll down to the footer | Find the phone number | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-7v1-15.jpg">
<img src="docs/user-story-testing/user-story-7v2-15.jpg">
<img src="docs/user-story-testing/user-story-9-15.jpg">
</details>


## Bugs

| **Bug** | **Fix** |
| ----------- | ----------- |
| Home page link stays highlighted when visiting another page | Change active atribute to the correct page |
| The user can submit a contact form input without a message | Add required attribute to message input field |
| Navbar divides into two rows on xs screen size | Add a media query to remove the right margin of the logo in the navbar on xs screen |
| Email overflows on xs screen size | Add a media query that makes the divs spread to 100% width on xs sreens to froce the content onto a seperate line |
| When viewed on tablets, the contact page has whitespace after the footer | Set min-height for body to 100vh |

## Deployment
The website was deployed using GitHub Pages by following these steps:
1. In the GitHub repository navigate to the Settings tab
2. On the left hand menu select Pages
3. For the source select Branch: master
4. After the webpage refreshes automaticaly you will se a ribbon on the top saying: "Your site is published at https://4n4ru.github.io/CI_MS1_BodelschwingherHof/"

You can for fork the repository by following these steps:
1. Go to the GitHub repository
2. Click on Fork button in upper right hand corner

You can clone the repository by following these steps:
1. Go to the GitHub repository 
2. Locate the Code button above the list of files and click it 
3. Select if you prefere to clone using HTTPS, SSH, or Github CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash
5. Change the current working directory to the one where you want the cloned directory
6. Type git clone and paste the URL from the clipboard ($ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY)
7.Press Enter to create your local clone.

## Credits
Images not referenced below are owned by the developer.

### Media
In order of apearance:
- [carousel-1](assets/images/carousel-1.jpg): Photo by <a href="https://unsplash.com/@heathergill?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Heather Gill</a> on <a href="https://unsplash.com/s/photos/pots-and-pans?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
- [news](assets/images/news.jpg): Photo by <a href="https://unsplash.com/@mareksminder?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Claudia Altamimi</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
- [meal-deal](assets/images/meal-deal.jpg): Photo by <a href="https://unsplash.com/@itssammoqadam?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Sam Moqadam</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a> 
- [chef](assets/images/chef.jpg): <a href='https://www.freepik.com/photos/food'>Food photo created by freepik - www.freepik.com</a>
- [menu background](assets/images/menu-background.jpg): <a href="https://www.freepik.com/vectors/background">Background vector created by pikisuperstar - www.freepik.com</a>
- [starter](assets/images/starter.jpg) Photo by <a href="https://unsplash.com/@margzu?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Margarita Zueva</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
- [main meal](assets/images/main-meal.jpg) Photo by <a href="https://unsplash.com/@keriliwi?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Keriliwi</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
- [kids meal](assets/images/kids-meal.jpg) Photo by <a href="https://unsplash.com/@itssammoqadam?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Sam Moqadam</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
- [dessert](assets/images/dessert.jpg) Photo by <a href="https://unsplash.com/@almapapi?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Krisztina Papp</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
- [wine](assets/images/wine.jpg) Photo by <a href="https://unsplash.com/@biljaminai?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Biljana Martinic</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
- [salad](assets/images/salad.jpg): Photo by <a href="https://unsplash.com/@itssammoqadam?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Sam Moqadam</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
- [fish](assets/images/fish.jpg): Photo by <a href="https://unsplash.com/@itssammoqadam?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Sam Moqadam</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
- [chicken](assets/images/chicken.jpg): Photo by <a href="https://unsplash.com/@itssammoqadam?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Sam Moqadam</a> on <a href="https://unsplash.com/?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
- [404 error image](assets/images/404-error.png): <a href='https://www.freepik.com/vectors/background'>Background vector created by freepik - www.freepik.com</a>
  
### Code
In order of apearance:
- The HTML for the responsive [Navbar with toggler](https://getbootstrap.com/docs/5.0/components/navbar/#toggler) was taken from the Bootstrap v5.0 documentation code snippet and combined with their [Navbar with Pills](https://getbootstrap.com/docs/5.0/components/navs-tabs/#pills)
- [Carousel](https://getbootstrap.com/docs/5.0/components/carousel/#with-indicators) on index page was taken from Bootrap v5.0 documentation code snippet
- CSS code to avoid whitespace below footer was taken from a forum post on [FreeCodeCamp](https://forum.freecodecamp.org/t/footer-white-space-below/191360)
- 404 page was build using description on [GitHub Docs](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-custom-404-page-for-your-github-pages-site)

## Acknowledgements
I would like to take the opportunity to thank:
- My mentor Mo Shami for his feedback, advice, guidance and support.
- My husband Jure Runje for his support, advice, help with testing, and for giving me some kids free time to work on my project.
- To the lovely people on the Code Institute Slack for providing peer code reviews.
- My parents who own the restaurant that inspired this website