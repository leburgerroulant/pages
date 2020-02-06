<h1 align="center">
  <a href="https://andy-osborne.github.io/Burger-House/index.html" target="_blank"><img src="https://i.ibb.co/MGCX6Z7/Burger-Logo.png" alt="Burger House logo"/></a>
</h1>

# Burger House

Milestone One Project: User-Centric Frontend Development - Code Institute

[Burger House](https://andy-osborne.github.io/Burger-House/index.html) is an up and coming restaurant based in Guildford, Surrey. The website is designed with mobile first philosphy as the majority of users these days have their mobile phones with them at all times and when hunger strikes,
they want to find a place to eat nearby that will satisfy their cravings - a poorly responsive website may lead a user to avoid that particular website. With this in mind, the website layout will easily adjust to their preferred method of viewing - desktop, mobile, or tablet, and retain its sense of flow.

I have used HTML, CSS and [Bootstrap Framework](https://getbootstrap.com/) to build this and the website will form part of my ongoing portfolio of work.

## Table of Contents

1. [**UX**](#ux)
    - [**User Stories**](#user-stories)
    - [**Business Owner Perspective**](#business-owner-perspective)
    - [**Customer Perspective**](#customer-perspective)
    - [**Developer and Business Goals**](#developer-and-Business-Goals)
    - [**Design choices**](#design-choices)
    - [**Wireframes**](#wireframes)

2. [**Technologies Used**](#technologies-used)

3. [**Features**](#features)
    - [**Existing Features**](#existing-features)
    - [**Features Left to Implement**](#features-left-to-implement)

4. [**Testing**](#testing)
    - [**Code Validation**](#code-validation)
    - [**Manual Testing**](#manual-testing)

5. [**Deployment**](#deployment)
    - [**To Run Locally**](#to-run-locally)

6. [**Credits**](#credits)
    - [**Content**](#content)
    - [**Media**](#media)
    - [**Acknowledgements**](#acknowledgements)

7. [**Disclaimer**](#disclaimer)

## Demo

A live demo of the website can be found [here](https://andy-osborne.github.io/Burger-House/index.html).

## __UX__

### User stories

### Business Owner Perspective

As a business owner perspective, the following stores would apply:

- As an owner, we want our website to be intuitive so customers can easily navigate themselves around our website and achieve the goal of their visit.

- As an owner, we want our website to be responsive so that customers can view the content of the website correctly, no matter the media device they view it on.

- As an owner, we want an interactive menu that our customers can use and navigate to various offerings we provide them with minimal effort.

- As an owner, we want a simple job section that will display what jobs we have available and an easy to use navigation so the user can get in touch with us.

- As an owner, we want our customers to be able to contact us easily through the use of a contact form that has some pre-loaded subject headers that the customer can choose from which can simplify and streamline the reason for them contacting us.

### Customer Perspective

From a customer perspective, the following stories would apply:

- As a user, I want to be able to intuitively navigate myself around the website so I can easily find the information I came to the website for.

- As a user, I want to be able to view the website on any media device that I am using and have the website be respoonsive so it adjusts itself correctly so that the content is understandable and looks good.

- As a user, I want to be able to navigate myself around the menu and the various sections and easily go back to the top of the menu or a different section with minimal effort.

- As a user, I want to be able to get all the contact information for the company as easily as possible with the option to leave my details for them to contact me.

### Design Choices

- During the initial design phase and through to the production of the website, I wanted to use a simplistic approach so not to overload the users with images and text which distracts their attention away from the actual content.
  In addition to this, a simplistic design gives the website a more modern look to it.

- For the main website content, I decided on a two shades of grey for the color scheme. The rational for choosing two shades of grey is that the lighter shade of grey can be placed ontop of the darker grey, which aids in highlighting
  the content within it.

- The navbar ontop of the website is a light blue color as this immediately stands out to the user without being overly in their face as it's a soft color.

- The font colors on the website have been chosen so they stand out to the user and are easy to read. I used the Google Dev tools to help choose colors that are a nice contrast     against their relative background color.

- I decided on using orange for the active hover for links and buttons, as this dramatically stands out to the user due to the contrast of their resting color and they immediately know this is where their cursor is and it's a clickable link.

- For the menu section, I toyed with Bootstrap's [card](https://getbootstrap.com/docs/4.4/components/card/) layout however; for the desktop screensize I felt that the design didn't fit with the rest of the website. Instead I decided to use a dotted border to house the various menu content sections which I felt added to the modern feel of the website.

- For the mobile section, I decided on using a collapsible menu as it made it more responsive for a mobile user and assisted them with navigating around the menu fluidly.

- For the job section, I used the [carousel](https://getbootstrap.com/docs/4.4/components/carousel/) component and combined it with the card layout from Bootstrap. I felt this was a good choice to show the available jobs as it cycles through the vacancies rather than showing the job offers in static positions on the
  page which would take up too much space and detract from the simplistic design of the overall website.

- The buttons were primarily based on Bootstraps btn class however; the color scheme of the button, fonts, and hover have been adjusted to compliment the website color scheme.

### Wireframes

- The wireframes for the initial layout of the website were drawn by hand and can be located [here](https://github.com/Andy-Osborne/Burger-House/tree/master/wireframes).

- When designing the initial layout of the website I provided a sketch for how I picutred the website to look on both large screens such as desktops and how it would look on small screens such as a mobile phone.

## Technologies Used

1. HTML - This was used for the overall structure of the website.

2. CSS - This was used for the overall and bespoke styling of elements on the website.

3. [Bootstrap Framework](https://getbootstrap.com/) - This was used to create the overall responsiveness of the website through the use of their flexible grid layout and style various features such as the navbar, accordian, cards, forms, buttons, and carousel.

4. [Font Awesome](https://fontawesome.com/) - This was used to obtain icons that were used within the website navbar and social links.

5. [Google Fonts](https://fonts.google.com/) - I used Google Fonts to obtain the fonts used on the website which are "Ibarra Real Nova" and "Roboto".

6. [GitHub](https://github.com/) - I used to store my repository for the project and record all my commits.

7. [GitHub Pages](https://pages.github.com/) - I used to deploy my website.

## Features

### Existing Features

Navigating around the website

- The website consists of five different sections which are: Home, About Us, Menu, Find Us and Job Section.

  - The navbar in the header section contains links to four sections which are Home, About Us, Menu, and Find Us as 95% of the users who visit the website are only trying to find one of these four things.

  - The footer contains links to About Us, Find Us, Join Our Team (Jobs section) and Privacy Policy (this link has been disabled as there is no content for it).

  - The logo in the top left of the website is hyperlinked to the Home page to follow the general rule for websites, so a user can click that and return to the front page.

  - On a Desktop/Large Table Screensize, the navbar links are on the right side of the screen and the restaurant logo is on the left.

  - On small screensizes, the navbar collapases into a toggler which the user can click to expand the menu and navigate from there. The logo in the left top left corner of the screen remains visible at all times.

Home Page*

- This features three cards which each have a picture, a header relating to their relavant section (Menu, Find Us, About Us) and a button that the user can click to navigate themselves to that section.

- On a small screen, the cards take on a column style so that the information remains easy for the user to read and action.

About Us

- This section implements the use of Cards to show the pictures of the two owners who established the restaurant and why they did it.

  - I have included a heading tag that asks if they "Share their passion" and a button under it with text that states "Join our team" which links to the Jobs page.

  - When viewing on a small screen, I have used ``row-reverse`` to shift the order and to make the bottom card shown above the text.

Menu

- I have included various buttons and the use of the accordian feature to add ease of use/navigation to the user:

  - Desktop/Large Tablets Screens - At the top of the menu, there are buttons titled Starters, Salads, Mains, Desserts which the user can click to instantly navigate themselves to those sections.
  - Mobiles/ Small Tablet Screens - The menu changes to an accordian meny which neatly and compactly displays the four sections of the menu. The user can click on their desired section and it expands to shows the menu items. The user can click on a different section of the menu and the previous section will close whilst the new section expands.
  - For all screensizes, each section of the menu has a button which uses the Font Awesome hand pointing up, once the user hovers offer it, the color changes to orange and has a hover over which tells them "Back to top of the menu". If they click this, it returns them to the top of the menu.

Find Us

- The primary feature of this section is the use of a form where the user can ask the restaurant to get in touch with them.
- The form contains a dropdown list for the subject heading which the user can use and select an available option from the list. This assists the restaurant as most subject headings will be consistent however; there is an additional option for the user should none of the preset subject titles match their need.

Jobs

- This section contains the use of the carousel feature which scrolls through the available job positions and includes a button which the user can click and will open the contact us page in a new window - so the user can still refer back to the vacancy they were looking it.

### Features Left to Implement

- __Google Maps__ - My initial design included the use of Google maps within the contact us section however; I implemented this and it worked correctly although this was later removed from the website. The reason for this is google maps requires a paid API key in order to correctly show the map on your website without an error message pop-up. I felt that showing the map and having this message on it takes away an element of professionalism away from the website although I will look to re-implement this into the design at a later stage.

- __Contact Us Form (Booking Functionality)__ - I want to improve upon the contact us form by adding in functionality of a user being able to book a table from the contact us section which will communicate with the backend system to make the booking. In addition to this, I want the form to submit information to the server so it log the information from the form.

- __Newsletter Sign Up__ - I want to include a Modal that pops up when the user visits the website and asks them to sign up to the newsletter. This modal will include a form where the user can input their email address & tick a box to confirm they are happy for us to contact them with promotions.

- __Privacy Policy__ - I want to include a modal or additional page that I can link the Privacy Policy hyperlink in the footer of the page to and contains the relevant Privacy Policy information.

## Testing

### Code Validation

- HTML - All code was run through the [W3C HTML Validator](https://validator.w3.org/) to ensure it was valid code and no errors were made.

- CSS - All styling was run through the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) to ensure it was valid and no errors were made.

### Manual Testing

- Manual Checking/Testing
  - I manually checked that there were no unused classes within the HTML and that any class given was correctly linked to a style rule.
  
  - I tested every link within my website to ensure the links work and are correctly linked to their relevant page.
  
  - I tested the responsiveness of the website to ensure that all content remains readable at various sizes, such as desktop, mobile phone and tablet.
  
  - I tested the menu function thoroughly at the various sizes mentioned above and that the buttons within the menu work as expected.
  
  - I tested that the form ``required`` functionality works correctly by trying to submit the form with empty data.
  
  - I tested the website within the Google Chrome, Mozilla Firefox and Microsoft Edge browsers to ensure it displayed correctly and address any issues that occur.
  
- I primarily built the website and tested each aspect of development through the use of Chrome DevTools to ensure that the website remains responsive at varying sizes. I used their pre-formatted screen size tool to check at what levels the website breaks and adjusted the code accordingly.

  - During the testing phase, I tried their iPad screen size which displayed my website correctly at varying zooms however; at 100% zoom I was unable to scroll down to the footer.
  
  - This lead me to test the website on a physical iPad and I did not have any issues on it as I was able to view the website correctly and scroll down to the footer.

  - I tested the available mobile phone screensizes and noticed when using the iPhone X, the hero images on About Us and Find Us shifted down so it left white space above or below the respective image.

  - I tested the website on a physical iPhone X and I did not experience this issue on the phone itself. The content of the website was responsive and easily visible. All links worked correctly.

  - There were no issues when testing the website on a Samsung S9 and the website was responsive and all content was easily visible. All links worked correctly.

- I tested the website within Mozilla Firefox and all content was displayed correctly and there were no sizing errors.
  - All links worked as expected.
  - The menu was easy to navigate around.
  - The form section ``required`` function works as expected.
  - I used the Mozilla DevTools to test the functionality on the Kindle Fire and no issues were experienced. All content displayed correctly.

- I tested the website functionality within Microsoft Edge and noticed:

  - The color I was using for the jumobotron text was not displayed correctly. I adjusted the font to a solid color and this lead to the text display correctly and lead me to use a solid color within the CSS code going forward.

  - There was an excess overflow of white space to the right hand side of the screen which is a unique issue to this browser. I used ``overflow-x: hidden`` within CSS to fix this however; at a later stage I would like to look into why this is happening only on the Microsoft Edge browser.

## Deployment

I developed this project using [GitPod](https://www.gitpod.io/) IDE and enabled me to push through all commits to GitHub.

The live version of this website is hosted using GitHub Pages and is deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.

To delpoy Burger House from its [repository in GitHub](https://github.com/Andy-Osborne/Burger-House/), I completed the following steps:

1. Log into GitHub
2. From the list of repositories, select Andy-Osborne/Burger-House.
3. Click on the settings button located just below the Fork option.
4. Scroll down the new page to GitHub Pages.
5. Select Master Branch from the dropdown menu.
6. After selecting Master Branch, the page will refresh and Burger House is deployed.
7. If you scroll back down to the GitHub Pages section after the page refreshes, you can grab your live link to your deployed site.

You can see a live example here:

<img src="https://media.giphy.com/media/fZ9GHVFi56W9l3gBxu/giphy.gif" alt="Burger House logo"/>

### To Run Locally

If you wanted to run this project locally and not use GitHub Pages, you can clone this repository directly into the editor of your choice by pasting `git clone https://github.com/Andy-Osborne/Burger-House.git` into your terminal. To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.

## Credits

### Content

All the content on the website was written by me, including the restaurant menu items and descriptions.

### Media

All the photos used on the website were taken from [Pexels](https://www.pexels.com/), which is a stock image library.

The Burger House logo was created by Rebecca Catlin for me to use for this project. It is important to note that after having the logo created, we researched "Burger House" and found a couple of restaurants that shared a similar name and logo style which was unintentional.

### Acknowledgements

The carousel feature was modelled after the bootstrap component and I would like to thank Sonar Systems and their YouTube tutorial [video](https://www.youtube.com/watch?v=n8ItscKLf7s) for understanding on how to implement it correctly. The overall carousel was modiied by me to allow the use of cards within the carousel itself and have a text box to display the job role, blurb and button.  

The sticky footer was created using the Flexbox technique tutorial provided by Css-tricks [site](https://css-tricks.com/couple-takes-sticky-footer/). This assisted me with coding the footer so it always stuck to the bottom of the webpage.

The CSS code used to create the interactive menu section was based around the code example provided on [site](https://alligator.io/css/css-only-click-handler/) although this was heavily modified to fit the purpose of creating a menu.

The icon logos were provided from [Font Awesome](https://fontawesome.com/), which provide free to use icons.

The idea for using an orange hover effect on social links was from the "Resume Project" by Code Institute.

I acknowledge that the logo and restaurant name is similar in design/name to [The Burger House](https://theburgerhouse.com/) and [The Burger Shop](https://www.theburgershopco.uk/).

A special thank you to my tutor for her help in the development stages of the project.

**This is for educational use.**