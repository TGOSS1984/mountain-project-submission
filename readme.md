# UK Winter Mountain Tours

Welcome to the **UK Winter Mountain Tours** website. This site is dedicated to providing expert-guided winter mountain hiking tours across some of the UK’s most famous peaks. Whether you're a seasoned hiker or a beginner, Tom's tours offer a safe and memorable hiking experience.

The website was setup to offer the general public an opportunity to experience some the of the UK's best mountain routes in the Winter with an experienced guide to support them along the way. Users of the website will be able to read about what is on offer with the guided tours, the regions available to choose from, the equipment that is required, a 'contact us' section for general enquiries & finally a booking form to book a tour.

This website has been built to be responsive on both mobile devices & larger screens such as tablets and desktop screens.

<p align="center">
  <img src="assets/images/wphomepage-devices.PNG" alt="Screenshot of booking form">
</p>

[Link to GitHub project](URL)



## Table of Contents
- [**Description**](#description)       
    - [User Experience](#user-experience) 
- [**Features**](#features)
    - [Main Features](#main-features)
    - [Features for Future Development](#features-for-future-development)
    - [Design](#design)
- [**Deployment**](#deployment)    
- [**Testing**](#testing)
    - [Browser Tests](#browser-tests)
    - [HTML Validation](#html-validation)
    - [CSS Validation](#css-validation)
    - [Lighthouse Tests](#lighthouse-tests)
    - [Solved Bugs](#solved-bugs)
    - [Unfixed Bugs](#unfixed-bugs)    
- [**Technologies Used**](#technologiesused)
    - [Languages](#languages)
    - [Technology](#technology)
- [**Credits**](#credits)
    - [Content](#content)
    - [Media](#media)


## Description

### User Experience

This website has been designed for individuals looking to explore the UK’s most iconic winter landscapes through guided mountain hikes. Tom Goss, an experienced hiker, offers tours across various regions of the UK, including:

- Lake District
- Snowdonia
- Scottish Highlands
- Peak District

Users can book their winter mountain tours, learn about the different regions, view required hiking equipment, get in touch for inquiries & finally, book a tour through the website. The site is designed to be responsive and user-friendly, providing a seamless booking experience and access to important information about the tours.

## Features

### Main Features

- **Navigation & Header**: A Navbar featured at the top of all pages. The Navigation Bar shows the name of the website along with the main sections/pages. All descriptions are clickable links to the pages / sections of the website. The Navbar items are designed so that when hovering over the color changes so the user can clearly see where they are clicking. The main header is fixed at the top of the page along with Navbar and is set to 70% opacity so content can still be visible beneath when scrolling. A png image icon has also been added to the right of the header as the main logo. The main header/logo & Navbar are responsive and will adjust accordingly depending on the device in use. On smaller smaller screens such as ipads, the header text size decreases, on the smallest screens the navbar is displayed as a hamburger icon and can be clicked to show the navbar items as a column as opposed to a row. On the smallest screens, the header becomes hidden and only the logo remains.

<p align="center">
  <img src="assets/images/navbar-header.PNG" alt="Screenshot of booking form">
</p>

<p align="center">
  <img src="assets/images/home-hamburger-column.PNG" alt="Screenshot of booking form">
</p>

<p align="center">
  <img src="assets/images/home-hamburger-column-smallest.PNG" alt="Screenshot of booking form">
</p>

- **Homepage**: Introduction to Tom Goss' UK Winter Mountain Guided Tours with a call to action to book a tour. The background image is of Crib Goch, a famous ridgeline on route to Snowdon, the highest mountian in Wales. This image shows Crib Goch & Snowdon in Winter conditions to set the mood of the website. In the center of the image is header with a description of the website along with a supporting tag that gives the user more information of what they can expect. Beneath this is a call to action which links to the booking section. Clicking the home button takes the user back to this page.

<p align="center">
  <img src="assets/images/homepage.PNG" alt="Screenshot of booking form">
</p>

- **About Section**: Details about the services and expertise Tom brings to his winter mountain hiking tours. Gives the user more information about what to expect on a guided tour and some information about why the website was created and what it offers.
- **Regions Section**: Highlighting various tour regions such as the Lake District, Scotland, Wales, and the Peak District with breif desriptions about some of the hikes available along with images. 'Cards' have been used to visually display this section. This section is responsive and is diplayed as four cards in a row on larger screens and will dynamically move to a stacked column on mobile devices.

<p align="center">
  <img src="assets/images/regions-section.PNG" alt="Screenshot of booking form">
</p>

- **Booking Section**: A direct link to the booking page.

<p align="center">
  <img src="assets/images/booking-section.png" alt="Screenshot of booking form">
</p>

- **Contact Section**: Contact form for any inquiries or questions. The 'Required' attribute has been added to all fields to tell the user that the field is required in order to submit.

<p align="center">
  <img src="assets/images/contact-section.PNG" alt="Screenshot of booking form">
</p>

- **Booking Page**: A page with a booking form to book your tour. The 'Required' attribute has been added to all fields to tell the user that the field is required in order to submit. Information such as name, email, address, date, group size, special requets has been added to the booking form 

<p align="center">
  <img src="assets/images/bookingpage.PNG" alt="Screenshot of booking form">
</p>

- **Equipment Page**: A page detailing the equipment required for hiking the mountains in Winter & why this is important. This page begins with an image of hiking equipment on a table. With aheader whihc begins on the bottom right but is responsive and moves to the middle of the image on smaller screen sizes. There are two paragraphs of text explaining the importance of the correct equipment and some safety information. Belwo this there is an accordion with four titles for Clothing, Equipment, Food & Drink & Emergency Items. These buttons can be clicked to expand/collapse to show a list of items below with further details. Thsi was added to reduce the visual length of lists contained within giving the user an option to drill down. At the bootm there is a Call to Action button whihc links to the booking page.

<p align="center">
  <img src="assets/images/equipment-page-head-p.PNG" alt="Screenshot of booking form">
</p>

<p align="center">
  <img src="assets/images/equipment-page-accordion.PNG" alt="Screenshot of booking form">
</p>

- **Footer with legal information & Social Media Links**: Links to Facebook, Instagram, and Twitter. Clicking these links opens a new tab with the relevant landing page. Legal information such as Terms & Conditions, copyright & contact information can be found here.

<p align="center">
  <img src="assets/images/footer.PNG" alt="Screenshot of booking form">
</p>

### Features for future Development
 - **Gallery/Detailed Route Descriptions & Prices**: Make the Region Cards clickable to see gallery of photos from these routes along with detailed information on route difficulty/length/location start & end pointys etcalong with pricing information.
 - **Terms & Conditions**: The Terms & Conditions contained in the footer would be a clickable link to a T&Cs page with full details


### Design

The website has been created with 3 pages (with the homepage having several sections), for easy navigation & seperation of information. All pages are linked with an intuitive navigation bar and can be accessed from each other. The nav bar has been designed to work on a range of devices. The general colour themes of the website are followed through each page for consistency. Contrast has been used for text along with image alternative descriptions for accessibility best practice.

#### Main Colours used

Use of Greys, Blacks and White's to provide a clean but also Wintery astetic to the website. The Call to Action buttons use a vibrant Yellow, not only to stand out to the user but also to link in with the hero image on the landing page and Winter Sun. 

<p align="center">
  <img src="assets/images/color-theme.PNG" alt="Screenshot of booking form">
</p>

#### Font

Used Roboto from Google Fonts across the website as the main font & for all headers used uppercase & letter spacing for clear descriptions. 

## Deployment

## Testing

## Browser Testing

## HTML Validation

Code was validated using HTML Validation 

- [HTML Validator](https://validator.w3.org/#validate_by_input)

<p align="center">
  <img src="assets/images/html-index-validation-screen.PNG" alt="Screenshot of booking form">
</p>

## CSS Validation

Code was validated using CSS Validation

- [CSS Validator](https://jigsaw.w3.org/css-validator/)

<p align="center">
  <img src="assets/images/css-validation-screen.PNG" alt="Screenshot of booking form">
</p>

### Lighthouse Test

Lighthouse Homepage test results - 

**Homepage**

<p align="center">
  <img src="assets/images/lighthouse-home-score.PNG" alt="Screenshot of homepage lighthouse result">
</p>

**Booking Page**

<p align="center">
  <img src="assets/images/lighthouse-booking-score.PNG" alt="Screenshot of booking form lighthouse result">
</p>

**Equipment Page**

<p align="center">
  <img src="assets/images/lighthouse-equipment-score.PNG" alt="Screenshot of equipment lighthouse result">
</p>

### Solved Bugs

### Unfixed Bugs

## Technologies Used

### Languages

### Technology

## Credits

### Content

- [Link to Bootsrap](https://getbootstrap.com/)
- [Link to Google Fonts](https://fonts.google.com/)

### Media

- [Link to Font Awesome](https://fontawesome.com/)
- [Link to pngimg](https://pngimg.com/)
- [Link to icons8](https://icons8.com/icons)