<a name="top-of-page">![Party Chef Logo created using FreeLogoDesign.org](/assets/readme-assets/party-chef-logo-readme.png)</a>

# PartyChef.ie :cocktail: #
## A website for Professional Private Caterers ## 
## Purpose: Interactive Frontend Development Project (Milestone Project 2) for Diploma in Software Development course at [Code Institute](https://codeinstitute.net/) ##
### Developer: Andrew McDonald - Contact me on GitHub :octocat: @ <a href="https://github.com/AndyMc3000"><strong>AndyMc3000</strong></a> ###
### Website deployed on GitHub Pages: [Click Me!](https://andymc3000.github.io/ci-ms2-party-chef/)

<hr>
<img src="assets/readme-assets/party-chef-am-i-responsive-screenshot.png" width="900">
<hr>

# Table of Contents #
1. [Introduction](#introduction-heading)
1. [User Experience Design (UX)](#user-experience-design)
1. [Development Process](#development-process)
1. [Website Features](#website-features)
1. [Technologies Used](#technologies-used)
1. [Testing & Bugs](#testing)
1. [Deployment](#deployment)
1. [Credits](#deployment)
<br>
<hr>

# 1. <a name="introduction-heading">Introduction</a> #

The Party Chef website is my Milestone 2 (MS2) project for the Diploma in Fullstack Software Development course at Code Institute. The underlying goal of the project is to meet and exceed the requirements laid out for the MS2 project by Code Institute. The high-level requirement of the MS2 project is to "..build an interactive front-end site. The site should respond to the users' actions, allowing users to actively engage with data, alter the way the site displays the information to achieve their preferred goals." 

This README refers to Party Chef as a fictional client of mine, where I have been hired to develop a website for the business owners to meet certain criteria (see UX section below). The principle technologies used in the development of the site are; HTML5, CSS3, and JavaScript. Other technologies include; the Bootstrap front-end framework, the jQuery library, and the EmailJS email service.

Party Chef is a private catering business with multiple office locations around Ireland. Party Chef is run by a professional team of chef's, service personnel, and party planners. The businesses offices are referred to as 'kitchens' on the website, as this is where food is prepared before being delivered to event/party locations. Customers can vist the kitchens in order to discuss and plan their events with the Party Chef team. 

#### [Back To Top ^ ](#top-of-page) ####

<hr>

# 2. <a name="user-experience-design">User Experience Design (UX)</a> #

The design of the Party Chef site was determined by assessing and quantifying the goals and objectives of the business owner ('client stories'), as well as the requirements of end users who will visit and use the site ('user stories'). Following the determination of client and user stories and their subsequent technical requirements, the site was designed using the principles of Jesse James Garrett's '5 Planes of UX Design'. The outcome or tasks created for each of the 5 design planes is outlinined below.

### 1. The Strategy Plane ###

The Strategy Plane, as defined by Jesse James Garrett "..incorporates not only what the people running the site want to get out of it but what the users want to get out of the site as well." 

Please see below details of the 'Client Stories' to detail the requirements of the Pary Chef business owner, and the 'User Stories' which highlight the requiremnts of end users of the Party Chef website.

#### Client Stories ####
> - [x] ???The main goal of the website is to attract new business for Party Chef, and provide value to visitors in the information is provides.???
> - [x] ???The website must show and promote the services which Party Chef provides.???
> - [x] ???The website must detail the various menu's on offer, and the cost of food/drink items on each menu.??? 
> - [x] ???The website must allow people to easily contact Party Chef.???
> - [x] ???The website must allow users to create their own menu from the menu items available, in order to get an idea of food/drinks costs for their party.???
> - [x] ???The website must also allow users to request a quote, based on their MyMenu items and other relevant information about their event (Party Date, Party Location). The quote request information (including items in the active MyMenu list of menu items) should be sent by email to the business owner. A copy of the quote request should also be sent to the user.???
> - [x] ???The website must allow users to find contact details for their local kitchen/office using an interactive Google Map (offices are called 'kitchens' on the site).???
> - [x] ???The website must promote links to Party Chef's social media channels.???
> - [x] ???The website must show photos of previous events.??? 
> - [x] ???The website must show customer testimonial quotes.???
> - [x] ???The website must be mobile-friendly.???

#### User Stories ####
> - [x] ???I want to see what kind of services Party Chef offers.???
> - [x] ???I want to see what kind of menu's (food & drink) Party Chef offer.???
> - [x] ???I want to find out where their 'kitchens' (offices) are located, and which is the closest office to me.???
> - [x] ???I want to see photos of the dishes in Party Chef menu's.???
> - [x] ???I want to see photos of previous events serviced by Party Chef.???
> - [x] ???I want to be able to see pricing for menu items.???
> - [x] ???I want to be able to create my own menu from the menu's of items offerred.???
> - [x] ???I want to be able to send my menu along with details about my planned event to the Party Chef team in order to confirm their availability to service my event, and to get a detailed quote inclusive of all costs."
> - [x] ???I want to be able to find links to the Party Chef social media channels.???


### 2. The Scope Plane ###

Based on the outcomes from the Strategy Plane, The Scope Plane determines what features, functionality, and types of content should be included within the scope of the project. Listed below are the functional specifications and content requirements decided upon for the Party Chef website. 

#### Functional Specifications: ####
* Build a responsive Website with 2 pages - a Homepage and a Contact page.
* Include a Navigation bar to highlight currently accessed page.
* Both pages should have a Jumbotron at the top of the page with relevant call-out messaging. The Homepage Jumbotron to include link to contact page in order to allow a user to find Party Chef contact details, and to send a query via a contact form.
* The Homepage should include a 'Features' section highlighting the Party Chef services.
* The Homepage should show various menu's (canpapes, starters, main course, something sweet, and drinks menus) each showing menu items listed within an accordian. 
* Shopping cart functionality should be built in so that menu items can be added to a 'MyMenu' list of items. The MyMenu should then be accessed via a button in the homepage Nav bar. Once clicked, the MyMenu list of items appears on a modal. Users can ammend quantites of the items they have selected in the MyMenu to get a total price for their food/drink selection. 
* The MyMenu should also have the facility to request a quote for an event/party. The request should include the food/drink items in a MyMenu list plus additional information about the event (date/time, location, etc.). The request will be sent to Party Chef by email. A copy of the request should also be sent to the user email address.
* The Homepage should include a Photo Gallery using a carousel to show dishes and menu items in party settings.
* The contact page must include all contact information for the Party Chef headquarters.
* The contact page should include an interactive map showing all the kitchen locations across Ireland. By implementing features of the Google Maps API, a user should be able to select an individual kitchen marker to get a pop-up of contact information for that particular kitchen.
* The contact page should also include a section highlighting social media channels.
* The contact page should also include a contact form so a user can ask a specific question of the Party Chef team.

#### Content Requirements: ####
* Both Jumbotrons should show images conveying people having fun at a party. Appropriate messaging should also be used to convey the key values of Party Chef.
* The features section on the Homepage should briefly, but completely, convey what the main services are and the the benefits of using them.
* Menu items should include a photo, a description, and the price per single serving of each item on the menus.
* Both photo galleries should show quality photos of impressive food layouts (Homepage Gallery) and recent events (Contact page gallery).
* Homepage should show the most glowing but brief Testimonial quotes along with the customer details.


### 3. The Structure Plane ###

#### Interaction Design: ####

Interaction design is defined as the "..development of application flows to facilitate user tasks, defining how the user interacts with site functionality". Inline with this principle, the pages were designed as follows;

1. The Homepage;
* It should have a navigation bar with individual links to each page and a 'MyMenu' modal. The navigation bar should also be fixed to the top of the page view.
* It should contain a call-to-action and button to allow a user to contact Party Chef. This should link to the contact page.
* It should contain a features/benefits section containing 4 principle features under the following rough heading titles; 'Who We Are', 'Our Services', 'Our Menu's', and 'What people say about us'.
* It should contain a list of menu's (each within its own accordion) under the following headings; 'Canap??s', 'Starters', 'Main Course', 'Something Sweet', and 'Drinks'. 
* The menu accordions should contain a list of menu item to include a photo, description, and an 'Add to MyMenu' button. When the 'Add to MyMenu' button is clicked, an item is added to the users MyMenu (i.e. a shopping cart modal). 
* The users MyMenu (a modal) can be accessed by clicking on the MyModal button in the Nav bar. Within the MyMenu modal, a user can change the quantity of an item or remove an item.
* A user can also send a copy of the menu to Party Chef, along with additional information which must be included, in order to request a quote and confirm availablity. The extra information will come from a form in the MyMenu modal which a user must complete. The form will ask for; Name, Email, Telephone number, Party date, Party start time, Location, Service Type. A copy of the quote request will also be sent to the user by email.
* It should contain a gallery of photographs highlighting recent events and food displays.
* It should contain a section to show Testimonial quotes.
* It should have a further navigation section in the footer. The footer will also contain links to all Party Chef's social media channels.

2. The Contact page;
* It should have a navigation bar with individual links to each site page.
* It should contain a section to show the address and phone number of the Party Chef Headquarters.
* It should include a Google Map with markers to show the individual Party Chef offices around the country. And when a user clicks on a marker, and 'info window' should popup to show the contacts details and address for that office.
* It should also contain a contact form to allow a user to submit a query to Party Chef.

#### Information Architecture: ####

Information Architechture is defined as; "The structural design of the information space to facilitate intuitive access to content" (Copyright 2000 James Garrett). As such Party Chef was designed to allows a user to find the information they need easily. For example, the navigation bar is fixed to the top of the page view so is always immediately accessible, and buttons and links are clearly visible and communicate their purpose in an unambiguous way.

The structure of the website and outline of page sections is outlined in the Sitemap. Click the link to view the <a href="assets/readme-assets/party-chef-sitemap.png"><strong>Sitemap.</strong></a>


### 4. The Skeleton Plane ###

Following on from the tasks decided upon in the Structure Plane, the Skeleton Plane is defined as follows; ".. The skeleton is designed to optimize the arrangement of these elements (such as the placement of buttons, tabs, photos's and blocks of text) for maximum effect and efficiency..".

With this in mind the following wireframes were created to detail the layput of the website pages and individual sections/containers. Please click the following links to view these wireframes.

1. <a href="assets/readme-assets/party-chef-homepage.png"><strong>Homepage Wireframe</strong></a>
1. <a href="assets/readme-assets/party-chef-contact-page.png"><strong>Contact Page Wireframe</strong></a>
1. <a href="assets/readme-assets/party-chef-mymenu-modal.png"><strong>'MyMenu' Modal Wireframe</strong></a>


### 5. The Surface Plane ###

Having completed the previous 4 stages in the UX design process, I moved on to making decisions around the design and styling of the website. The Surface Plane focuses on the styling of images, backgrounds, fonts, and colours used on a website. The details of these decisions are listed here;

1. Colours - The color scheme for the website was chosen from a selection of colours I considered using tools on the [Coolors.co](https://coolors.co/) website. The color schemes chosen, along with their HEX values, is shown here;
<img src="assets/readme-assets/party-chef-coolors-pallette.png" width="450">

1. Font - I used the Google Fonts website to help me decide on a font to use. I wanted something simple yet modern at the same time - not too bold, and something a little different. I decided upon a font called 'Blinker' for headings, and the 'Montserrat' font for paragraph texts. An example of these fonts can be seen here;   
<img src="assets/readme-assets/party-chef-google-fonts-blinker.png" width="220">
<img src="assets/readme-assets/party-chef-google-fonts-montserrat.png" width="220">

1. Logo Design - I created the Party Chef logo using tools on [FreeLogoDesign.com](https://www.freelogodesign.org/).

1. Images - I mainly used photos taken from the [Unsplash.com](https://unsplash.com/) website. On Unspalsh.com I was able to create a collection of relevant phtotos. The naming convention for each photograph includes a referenece to the photographer name and the Unsplash item code. The Alt attribute for each photograph also includes the photographer name.

1. Icons;
    * I used [Font Awesome](https://fontawesome.com/) icons to add icons to section headings. 
    * I created and added a Party Chef Favicon to the page headers.
    * I used [Flaticon](https://favicon.io/) icons for the social media section on contact.html.

1. Gallery - I decided to use a Bootstrap Modal as a container for my Carousel Gallery.

#### [Back To Top ^ ](#top-of-page) ####

<hr>

## 3. <a name="development-process">Development Process</a> ##

I drew up a process to follow for developing the Party Chef website. This is listed in sequence below.

1. Design - I firstly designed the site based on the Client/User Stories requirements, and by creating wireframes/sketches.
2. Structure - I then wrote the HTML code for all pages including; navigation, footers, sections, modal gallery, forms, and Google Maps section.
3. Interactive Functionality - I added in any JavaScript elements to the site. Those being; the Google Maps API for a map with custom markers and 'infoWindows'.    A JavaScript Shopping Cart plugin. JavaScript to send form data via email using the EmailJS service. And Bootstrap JavaScript to manage form validation.
4. Content - I then added text content to sections (lorem ipsum/placeholder text), and images to galleries. 
5. Style - I then added colours and fonts and wrote CSS rule sets and media queries in order to style the website and make it responsive.
6. Responsive - I made sure all texts/headings, images, and container elements transform approprately and look good when viewed on different devices such as:        mobile phones, tablets, laptops, large screen PC's, and large TV's. 
7. Review - I did a last review of all code (formatting, beautifying etc) and content, fixing anys bugs/typo's etc as I did so.
8. Testing - I validated my HTML, CSS, and JavaScript code, and tested functionality of site elements across a range of different devices and browsers. I then fixed any bugs found.


#### [Back To Top ^ ](#top-of-page) ####

<hr>

## 4. <a name="website-features">Website Features</a> ##
* Bootstrap Navigation Bar on index.html and contact.html.
* Bootstrap Jumbotron on index.html and contact.html. 
* Bootstrap Accordions for menus.
* Bootstrap Responsive Grid system.
* JavaScript shopping cart used for MyMenu system.
* EmailJS code for sending form and MyMenu data by email.
* Bootstrap Carousel Slider Modal Gallery.
* Google Map with custom markers and infoWindow's.
* Bootrap Forms for MyMenu Modal on index.html and Contact Form on contact.html.
* Bootstrap Form validation code.
* Social Links in Footers.
* Navigation links in Footers.

#### Future Features ####
* An End user could be able to book and pay for an event online. This would require the integration of a booking system and a billing system.

#### [Back To Top ^ ](#top-of-page) ####

<hr>

## 5. <a name="technologies-used">Technologies Used</a> ##

<img src="assets/readme-assets/technologies-used-logos-readme.png" width="330">

I used the following technologies, services, and devices to develop, style, deploy, and test the Pary Chef website;
<br>
* HTML5 - The site was developed using HTML5 markup language.
* CSS3 - The site was styled and in some cases made responsive using CSS3.
* JavaScript - Used for MyMenu functionality, Google Map, and EmailJS service.
* Bootstrap - I used the Bootstrap framework for implementing some sections and features of the website.
* EmailJS - I used the EmailJS email service to send Form and MyMenu list data by email to users and to Party Chef.
* GitHub - I set up a free repository on GitHub.com to maintain a master of all website files, content, and resources.
* GitPod - I used the free GitPod.io Integrated Development Environment to write and develop the code for the website.
* Github Pages - I used the free GitHub Pages hosting service to deploy/publish the live website on the internet.
* Balsamiq - I used the Balsamiq application to create the website sitemap and webpage wireframes.
* W3C validators - I used the W3C HTML5 and CSS3 code validators to validate my HTML and CSS.
* JSHint - I used jshint.com to validate my JavaScript code.
* Responsive Viewer - I used a Chrome Browser Extension called Responsive Viewer to emulate the presentation of the website on multiple device sizes and types.
* AmIResponsive - I used the [AmIResponsive](http://ami.responsivedesign.is/) webpage to view site responsiveness across devices.
* Apple Preview - I used the Apple Preview image editor application to crop and resize photo's and images. 
* Apple Pages - I used the Apple Pages word processor to manage and edit text content for the website. 
* Apple Keynote - I used Apple Keynote as a sketch pad to test content and review/edit content/images.
* Apple Hardware - I used a MacBook Pro to develop the site. I also used an Apple iPhone, Apple TV, and Apple iPad for testing the website.

#### [Back To Top ^ ](#top-of-page) ####

<hr>

## 6. <a name="testing">Testing</a> ##

Testing was completed under the below headings. A detailed testing document can be seen <a href="https://github.com/AndyMc3000/ci-ms2-party-chef/blob/64ce133eb8b56d1dba8d335c47b9f7f6aa89151f/testing.md"><strong>Here - testing.md.</strong></a>

#### Testing Headings ####
1. Development Testing
1. User & Client stories Testing
1. Code Validation
1. Device Testing
1. Browser Testing

#### Bugs Discovered / Remedies ####
1. Issues remained with the functionality of forms when they are not completed in full. These validation erros have now been resolved with help from Tutor support.
2. Issues remained with multiple alerts appearing when a product is removed from the MyMenu. This has now been resolved with help from my Mentor, Rueben Ferrante.
3. The contact forms don't clear their contents once the send buttons are sent. This has now been resolved with help from my Mentor, Rueben Ferrante.
4. The JavaScript code was not commented fully. This has been resolved.
5. The Google Chrome Dev Tools console logs a warning which reads: 'Error with Permissions-Policy header: Unrecognized feature: 'interest-cohort'.' I found from a thread on StackOverflow that this relates to a "new header used to block Google's new tracking technology called Federated Cohorts of Learning (FLoC)." I then found that GitHub has added this new permission policy header to all pages. As such the warning is not within my control to fix as my site is deployed on GitHub Pages.

#### [Back To Top ^ ](#top-of-page) ####

<hr>

## 7. <a name="deployment">Deployment</a> ##

This site was developed by firstly setting up a GitHub repository to store the website files. GitHub is a free online code hosting platform for websites or web applications, which enables version control and collaboration during the development of a project. A repository on GitHub containes all of a project's files and each file's revision history. You can learn more about GitHub and repositories here: [Click here to go to GitHub](https://docs.github.com/en/free-pro-team@latest/github)

I then used the online GitPod Integrated Development Environment (or GitPod IDE) to write the code for the website. Once I was happy with a section of code I commited or saved those to a staging area. Then on a regular basis I commited changes to the working version of the website on GitPod. These commits included a short description of what the changes are. I would then 'push' those changes from the GitPod IDE to my GitHub repository where the master set of files was updated. You can learn more about GitPod here: [Click here to go to GitPod](https://docs.github.com/en/free-pro-team@latest/github)

Early on in the development process I also deployed the website to a live web address using GitHub Pages. GitHub pages is a free static-site hosting service. It takes HTML, CSS, and JavaScript files directly from a GitHub repository and publishes a website with them. Once setup, any changes you make on your IDE which are subsequently 'pushed' to your GitHub repository, are automatically updated on GitHub Pages too. The published GitHub Pages website can be seen here: [Click here to go to Party Chef](https://andymc3000.github.io/ci-ms2-party-chef/)

Here are the steps I took to deploy the website on GitHub Pages;
1. Login to GitHub.
1. Select 'Your Repositores' by selecting the dropdown button on the your account icon at the top right-hand corner of the screen. 
1. When you get to the Your Repositories page, select the project you want to deploy.
1. When in the individual repository page, click on the Settings icon from the lists of options above the repository file list (settings can be seen listed on the far-right of this list).
1. Once in the settings page, scroll down the GitHub Pages section near the bottom of the page.
1. Under the Source section, select the branch of the project you want to deploy from the first dropdown box (normally the master branch).
1. Also under the Source section choose the folder of the files you wnat to deploy (normally '/root').
1. Once you have made your selection, click Save. This will deploy your site to a unique URL. Once the site has been deployed, green text with a tcick mark will appear above the Source secion to notify you that deployment has been successful, and will also show you the URL for the website.

I deployed the website early on in the developmnt process, as it useful to be able to examine the website on various physical devices in its live state. Also, while the GitPod IDE has the ability to show a preview of changes to a project, sometimes that does not pick up or display issues which would appear on a live site. For example, when I deployed my website on GitHub Pages initially, I found that it was not reading my CSS file, so no styling was appearing on the site. Yet the Preview tab in GitPod was reading the CSS file correctly. I found that a typo relating to the CSS file source address in my page headers caused the issue for the deployed site, while GitPod Preview did not pick it up. By having the deployed site up and running, I was able to address and correct the bug early in the development process.

The working version of the Party Chef website deployed on GitHub Pages can be seen here: [Click here to view deployed website](https://andymc3000.github.io/ci-ms2-party-chef/)

#### [Back To Top ^ ](#top-of-page) ####

<hr>

## 8. <a name="credits">Credits</a> ##

1. Coding Websites - I regularly used website to help me learn how to code certain elements/features. I also copied code snippets from these sites in some cases. These websites include; 
* [W3Schools.com](https://www.w3schools.com/)
* [Mozilla MDN Web Docs](https://developer.mozilla.org/)
* [Bootstrap](https://getbootstrap.com/)
* [GitHub.com](https://github.com/)
* [StackOverflow.com](https://stackoverflow.com/)
* [CSSTricks.com](https://css-tricks.com/)

1. BBC Good Food webite - I copied the images and descriptions for 50 dishes on the BBC Good Food website to poulate the different menus on the Party Chef homepage. I edited some of the text descriptions but didn't edit any of the images. I did prefix each image filename with a number, but otherwise the filename is as the BCC Good Food website named them. Learn about the BBC Good Food website here: [BBC Good Food](https://www.bbcgoodfood.com/)

1. Javascript Shoping Cart Plugin -  I used a Javascript plugin for the MyMenu feature on Party Chef. This was copied from code supplied by a GitHub user called WebDevSimplified who offers online coding course on YouTube. See that users profile here: [WebDevSimplified](https://github.com/WebDevSimplified). See the code repository for this plugin here: [Introduction to JavaScript Lesson 1](https://github.com/WebDevSimplified/Introduction-to-Web-Development/tree/master/Introduction%20to%20JavaScript/Lesson%201).

1. jQuery code used to stop Bootstrap form validation after a form was submitted in emailjs-contact-page-contact-form.js - I had a bug with form submission where Bootstrap validated the form again after 'submit' and 'reset'. As the form had been reset, this resulted in validation errors appearing on the blank form. I found some jQuery code on a GitHub issues thread which fixed the problem when I applied the code to my EmailJS JavaScript file. This thread was owned by a GitHub user called Cina Saffary. See the GitHub thread here - ['Resetting form doesn't clear validation errors'](https://github.com/1000hz/bootstrap-validator/issues/68).

1. EmailJS code - I copied relevant JavaScript code from the EmailJS website in order to create my 2 JavaScript files which send the emails from the forms on inde.html and contact.html.

1. Google Map with custom markers and InfoWindows - I used a YouTube video to help with implementing the Google Map API and adding custom markers and InfoWindows. That video was created by Pradip Debnath. See Pradips GitHub profile here: [Pradip Debnath](https://github.com/itzpradip). See the YouTube video here: [Google Maps API Tutorial | Custom Marker Icon | Multiple Info Window](https://www.youtube.com/watch?v=Xptz0GQ2DO4)

1. Colours - I used the Coolors.co website to help me decide on a colour scheme for the webite. This website allows you to create your own colour palettes or to use one of thiers. See more about the Coolors.co palette catalogue and tools here: [Coolors.co](https://coolors.co/). 

1. Font - I used Google Fonts for the fonts on the website. See more at: [GoogleFonts.com](https://fonts.google.com/)

1. Icons - I used FontAwesome and Favicon for all icons on the website. See more at: [FontAwesome.com](https://fontawesome.com/)

1. Design Principles - The design of this website employed the principles of 'The 5 Planes of UX design', which was created by Jesse James Garrett in his book; The Elements of User Experience: User-centered Design for the Web (2002). See more at; [Jjg.net](http://www.jjg.net/elements/)
  
1. Company Logo - The Party Chef logo was created using tools on the FreeLogoDesign.org website. See more at; [FreeLogoDesign.org](https://www.freelogodesign.org/)

1. Wikimedia commons - Technology logo's.


### Acknowledgements ###

In order to get design ideas, I took inspiration from a number of industry relevant websites.
These websites are;

No. | Business Name | Website | Description
--- | ------------- | ------- | -----------
1 | **The Whole Hog** | [TheWholeHog.ie](https://www.thewholehog.ie/) | A team of professional chefs who deliver event catering across the whole of Ireland.
2 | **Prestige Catering** | [PrestigeCatering.ie](https://www.prestigecatering.ie/) | Prestige Catering is a caterer recognised as one of Cork???s best catering companies.


### Additonal Support ###

I also received help and support from;
* Reuben Ferrante - Code Institute Mentor - Slack Username: [reubenfer_mentor](https://code-institute-room.slack.com/team/UKD9L615F) - Reuben is my new Mentor and was hugely helpful with helping me with my JavaScript code, having jumped in at a late stage in the project. Reuben also helped me with fixing issues for the resubmission of my project.
* Allen Thomas Varghese - GitHub username: @allentv - my initial mentor at Code Institute for this project.
* Anna Greaves - Full Stack Developer and Content Developer at Code Institute - GitHub profile here: [@AJGreaves](https://github.com/AJGreaves)
 - I took inspiration from Anna's Family Hub project on GitHub. In particular I found Anne's README.md and Testing.md files very helpful. See that repository here: [FamilyHub](https://github.com/AJGreaves/familyhub)
* The Student Support team at Code Institute.
* The Tutor team at Code Institute.

#### [Back To Top ^ ](#top-of-page) ####

<a name="top-of-page">![Party Chef Logo created using FreeLogoDesign.org](/assets/readme-assets/party-chef-logo-readme.png)</a>
