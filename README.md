 ![GitHub Logo](assets/images/Logo.jpg)

![GitHub Responsive](assets/images/responsive.jpg)


# Coco & Co Sweet Bakes Shop
## https://edita-l.github.io/Project1EL/

---
## **Contents**
1. Introduction
2. UX
3. Wireframe
4. Visual Identity
5. Site Overview
6. User Stories
7. Testing
8. Technologies
9. Acknowledgments and Thanks

---

## Introduction

*Note: This site is for a fictitious business, created purely for the purpose of my 1st Project. It is my first Milestone for the Code Institute Diploma in Full Stack Development*

Coco&Co is a Bakery shop in Bath, offering to buy a selection of English, French and Lithuanian cakes, baked from mainly locally grown and sourced produce. It is created by and for lovers of sweet bakes who are looking to buy a treat in Bath area.

---

## User Experience (UX)

I have attampted to create an uncluttered and responsive site with a very simple and clean home page where the main feature is an inviting background and an easy access to The Cake page link, with a range of products is displayed.  Full viewport sets the tone for the rest of the site. The goal is to give a clear idea of products offered and use bright and inviting colours.

- **The header and footer:**
    * Consistent throughout Home, Cakes, Order and About Us pages;
    * Navigation bar and Logo in the center of the Header allows quick access to each page without having to click Back button;
    * Footer Bar running though each page gives Opening times, Location of the Shop by clickbale Find Us Link (which takes user to google maps), clickable phone number and email address as well as links to social media accounts;
    * Design is identiacal throughout the site on all pages for continuity. 

*   **Home page:**

    The home page design is very simple - the main feature is a  relavant background photo that covers the full viewport. The goal is to give a clear inclination of products offered and easy access to product display page.

    In the center a jumbotron was used, within which is a Button Link The Cakes page. This invites and allows an easy and quick access to viewing products.
    
    Concept for my site is to have many sections interlinked, which I feel makes it more accessible.

* **Cakes page:**

    The simple and responsive layout is achieved by using a grid flex system with different areas of products offered, divided into main English/French/Lithuanian sections as well as photos to give clear idea of product and to enhance the visual experience.

    Each section has four cakes options with names and brief description of each.

    There is a link to the ordering page from the bottom of each product card as well as an easy option of getting back to Home page without having to use Back button - by clicking on the Logo at the top of page.

    The main page heading gives clear information about the prices and reminder for any allergy notifications.

* **Order page:**

    The main feature of the Order page is a Form Section, giving options for entering different style data and submitting information via clickable button once user is ready to send the order/request.

    It also has a full background cover image to keep in style with the rest of the site and within bakery theme.

* **About Us page:**

    About page follows the theme with another background image of baking ingredients, and includes three dividers with some information about ethos of business.

Due to having a few large images on the site which took long to load and for the purpose of improving user experience, I have compressed the images using tinypng.co.

---

## Wireframe

The wireframe was designed using Balsamiq.
It has a basic intial structure, which remained throughout the project, with the styling slightly changed/enchanced for better viewing experience.

Below is a link to all my wireframes:
## ![My Wireframes](pdfs/wireframe-project1.pdf)

* First page shows initial design idea for Home page, which has been since styled slightly differently to have more readable page layout. The main feautres are call of action button in the centre, preceeded by some introductory text. The Logo and Nav links are located in the header, with contact and social account information in the footer.
* Second page shows the layout of products, split into three diffrent sections layed out along the page.
* Third page - order form, shows original simplified idea for sending potential enquiries.
* Final page is for displaying three short sections of information about basics of the company history and ethos.

---

## Visual Identity

 For the logo, I wanted to use a simple word format in a classical font, to make it universal and appealing.

 I have used mainly combination of three colors, to enchance contunuity, seperate sections and to keep it uniform.
 The Cake page has an addition of extra color, to seperate sections and to make it slightly different central point of site.

 The Header and Footer are in the same font color, with clickable link changing to indigo on hovering, again, to keep it uniform and to give predictability for user.

 ## Site Overview

 Images below show overview of the site:
 ![GitHub Responsive](assets/images/so1.jpg)

 ![GitHub Responsive](assets/images/so2.jpg)

 ![GitHub Responsive](assets/images/so3.jpg)

 ![GitHub Responsive](assets/images/so5.jpg)

---
## User Stories

*The site is designed for people looking to buy some cake either by placing order online or by visiting shop in Bath.*

**Users:**
* As a user, I'd like to easily see information about shop address and opening times.
* As a user, I'd like to see different cakes available to buy and to read brief description of them.
* As a user, I'd like to know if business is sustainable and dedicated to being enviroment friendly.
* As a user, I'd like to see photos and social media posts showing the business as it operates on a daily basis.
* As a user, I'd like to be able to contact the shop easily either by phone or email.
* As a user, I'd like to access location through google maps by a click and not having to type in address.

Coco&Co business owner:
* As a business owner, I'd like to show potential customers that they will have a good choice of cakes, clearly priced.
* As a business owner, I'd like for potential customers to have a clear idea of our business location and opening times.
* As a business owner, I'd like for potential customers to have an understanding of where we come from and our ethos as a business.
* As a business owner, I want to offer customers the option of ordering via the site.
* As a business owner, I'd like to share a glimpse of our life through our social media posts.
* As a business owner, it's important to me that any user/ potential customer viewing the site has the best experience and is able to easily access all the relevant sections with one click.

---

## Testing 
My website has been tested through the GTMetrix site,   
[GTmetrix](https://gtmetrix.com "GTmetrix Homepage")
Below is a screenshot of the results achieved, with performance and structure graded A by GTmetrix.

![GitHub Responsive](assets/images/gtmetrix-el.jpg)

I have tested the site on a number of occasions throughout the building process, so that I could see it from different devices such as my mobile, tablet and PC and check for responsiveness.

The site was tested on CSS and HTML Validator sites. There were some syntax mistakes, missed characters etc, that have been updated.

### **Issues and Changes Implemented**

During this testing I realised that I had to make some design changes to areas that I was not satisfied with, to make it more easy to navigate, user firendly and improve the viewing experience on the mobile devices.
I have therefore made many changes as I went along in order to make it more responsive or easier to navigate. Some of these changes are listed below:
* Initially Index Page had just navigation link listed at the top and hero image, followed by footer. I have added the central To Cakes call of action button to make it easier to reach the product page.
* The Header was not responsive enough on mobile devices so I have used pure CSS code to make nav bar more responsive.
* The Header components were aligned to the sides of the screen to start with, but were centered to make it more appealing from UX point of view.
* The Index page background image and call of action button were initially set as separate divs and would overlap when tested on different screen sizes. This was overcome by using bootstrap jumbotron.
* The footer was changed from original p style into unordered list to make it more readable on different devices.
* The Order section was found to not fit into smaller screens properly, adding some padding have corrected it.
* Some of the background colors (on Index and Order pages) have needed adjusting to make the text displayed over them more easy to read.
* While testing I realised few links were not working where I have mistyped addresses, those were rectified.
* About Us page sections where not aligning properly on different size screens, I have added a flex grid to overcome that issue. It has also appeared to have too long paragraphs to keep visitor interested, which were concentrated and shortened since.
* Having noticed that images overstretch horizontally on larger screens, max-width has been added to each page main section to resolve this.

*Changes I would still like to add:*
* *Setting buttons on Cakes page to be at the same line of viewing. I have tried different styling and html structures but havent managed yet to achieve it.*
* *Improving Order Form, to have an option of adding things to basket, continue to the payment page etc.*

**As a User I was able to:**
* See contact information clearly either straight away at the bottom of page or by scrolling down on smaller devices 
* Be taken to the product page by clicking on central button in Home page
* See images of products and click on 'Order' link from Cakes page
* Get basic information about business ethos from AboutUs page accesible from top nav bar
* Access company's social media accounts from footer on each page.
* Contact business by email or phone by clicking a relevant field in footer and not having to type text/numbers in.
* Forward order and any comments/enquiries by clicking on Order tab in Nav Links and filling Order form.

---

## Technologies
**Languages and Frameworks**
* HTML
* CSS

**Tools Used**
* Balsamiq: for creating wireframes
* Github and Gitpod: for creating and editing code
* Font Awesome: used for icons
* Google Fonts: Quicksand and Roboto fonts imported from google fonts
* Responsive Viewer: a google chrome extension used to test site at different screen sizes
* TinyPNG used to compress images
* W3C Validator used to validate HTML code
* CSS Validator used for checking CSS code
* Am I Responsive used for showing site views for different screen sizes
* Bootstrap for Jumbotron used on Index page

---

## Acknowledgments and Thanks
* Massive thank you to Felipe Alarcon for all the support, advise, ideas and feedback.
* David Walsh Blog for reset css
* Pure CSS for styling Header navigation links
* MarkdwonGuide
* Stack Overload
* Unsplash and BirzuDuona for images
* Google

---






 






