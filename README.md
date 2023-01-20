# Paint-in Cafe
This website is built for all the residents or tourists of Ireland(ROI) looking to do a creative activity in Dublin,Ireland.The website is based on a fictional cafe that allows you the unique experience of painting with watercolors while also eating from the cafe.This website is designed to be responsive to allow users from any location to view the cafe website on any device.

![Website shown in different devices](documentation/am-i-responsive.png)
## CONTENT
* [User Experience(UX)](#user-experience(ux))
  * [Brief](#brief)
  * [User Objectives](#user-objectives)
* [Design](#design)
  * [Color Scheme](#color-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Wireframes](#wireframes)
* [Features](#features)
  * [General Features Per Page](#general-features-per-page)
  * [Future Implementation](#future-implementation)
  * [Accessibility](#accessibility)
* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks,-libraries-&-programs-used)
* [Deployment & Local Development](#deployment-&-local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)
* [Testing](#testing)
  * [Automated Testing](#automated-testing)
    * [W3C Validator](#w3c-validator)
    * [Lighthouse](#lighthouse)
    * [Wave](#wave)
  * [Manual Testing](#manual-testing)
    * [Testing User Stories](#testing-user-stories)
    * [Full Testing](#full-testing)
  * [BUGS](#bugs)
    * [Known Bugs](#known-bugs)
    * [Solved Bugs](#solved-bugs)
* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgement](#acknowledgement)

## User Experience(UX)
### Brief
Paint-In Cafe is a Cafe based in Dublin, Ireland. Visitors of the cafe are provided with the necessory stationaries to paint with watercolors while having the option to order from our food menu as well.It is the place to go to when you want to do a creative activity to do with any number of people.This website is created for any users/ first time visitors to understand the cafe's concept, get contact details, find location of the cafe or send in an inquiry to the "paint-in cafe's " staff inorder to accomodate their specific needs.
### Key information 
* The cost involved (Cafe and experience)
* Do you need prior experience in painting?
* Is there an age limit?
* Do i need to book?
* Opening times and location
* Contact details incase you need to get clarification on a specific problem.
* Allergens included in cafe food, veg and vegan options?
* Is the food halaal?
* How to book for an event?- event enquiry
* Any updates on the cafe?
### User Objectives
#### Customer Goals
* To be able to view the site on different device sizes.
* To allow potential customers to find out about Paint-In Cafe and where its located.
* To allow potential customers about the concept of the cafe and understand what they need to do to visit.
* To ensure visitors have access to contact details incase they have any questions with regards to the cafe.
* To ensure customers know exactly what they get out of the experience.
* To allow customers to be able to book tables in case of events.

#### First Time Visitor Goals
* To be able to navigate around the website with ease to find any information.
* To ensure that the visitor can find the enquiry form to submit in the case of wanting to book a table for an event.
* To allow visitors to see gallery pictures of the cafe and paintings done at the cafe.
* To allow visitors to view the menu of the cafe on the site to see their options for food.
* To allow visitors to have contact information incase they have any questions. 
* Ensure visitors can find out about location and opening times.
#### Returning Visitor Goals
* To be able to find any updates about the cafe on the home page.
* Find contact details of Cafe in case they have any questions with regarding to their experience at the cafe.
* To be able to find their own pictures in the gallery
#### Site Owner's Goals
* To ensure first time visitors have a good experience navigating through the web.
* To generate traffic to website so more people know about the cafe. 
* To ensure visitors understand the concept of the cafe and how it works.
* To provide the visitors all the information they need before visiting the cafe for the first time.
* To ensure visitors know that visitors do not need any prior experience in painting to visit.

## Design
### Color Scheme
![Inserting paint-In cafe color palette](documentation/paint-in-caf%C3%A9-color-palette.png)
I initially inserted the color palette above thinking that the colors appear the same(atleast almost) on all devices.After finishing the website and i checking my website on other devices i realised that my colors looked very different from my own laptop. 
I thought the color **#67D387** was a pastel mint green color but it appeared bright green on other devices.The **#7B9F82** was supposed to be a grey color which turned out to be a shade of green on other devices. I decided to change these two colors to accomodate my device and other devices. I tested the color **#C4C3C7** and **#ADD0B3** below and they looked more like the colors i wanted in all the other devices.
I used pastel green color because i find green to be a calming color and i found that a lot of art websites used **pastel** colors. I thought the dark red gives a good contrast to the pastel green and it may also be reminscent of the cafe interior and dark furniture. The white and grey helps with the flow and balance of the two contrast colors.I decided againt using the **#F0996A** because the color ddnt flow nicely with the design and i ddnt know how to incorporate without it clashing with the other colors.

**Final Color Palette**
![Inserting changed color palette](documentation/final-color-palette.png)


---

### Typography
I used these two Google Fonts for headings and other texts because they pair well together.
* [Playfair Display](https://fonts.google.com/specimen/Playfair+Display)-This is a transitional serif typeface and i used this for headings.
* [Open Sans](https://fonts.google.com/specimen/Open+Sans)-This is a humanist sans serif typeface and i used this for paragraphs and other texts.

### Imagery
All images in the website were taken from a free image source called Pexels.I have included the links to the images in [Credits](#credits) section.
* [Pexels website](https://www.pexels.com/)-Used for all images and videos in website.
* [svgrepo](https://www.svgrepo.com/svg/105795/paintbrush-and-palette)-Used for the logo and favicon.
### Wireframes
Wireframes for mobile, tablet and desktop view
* **HOME PAGE**![Home page wireframe](documentation/home-wireframe.png)
* **ABOUT PAGE** ![About page wireframe](documentation/about-wireframe.png)
* **CAFE PAGE** ![Cafe page wireframe](documentation/cafe-wireframe.png)
* **GALLERY PAGE** ![Gallery page wireframe](documentation/gallery-wireframe.png)
* **EVENTS ENQUIRY PAGE**![Event enquiry page wireframe](documentation/event-enquiry-wireframe.png)

The final designs look very different to initial wireframe designs because i started thinking more and more about user experience and design flow and realized i had to change a lot.
---
## Features

### General Features Per Page

The website has 5 pages in total. The pages `Home`, `About`,`Cafe`, `Gallery`,`Event Enquiry` are placed as navigation links on the first page on the top rightside if the website is displayed on desktop, laptop or tablet. The navgation links to these pages are removed and placed as a hamburger toggler button when viewed on a mobile.This is done to to save space avoid looking cluttered in mobile-view.Each page will have the header element and footer element that will be consistent thoughout the pages.The website is designed to be easy to navigate for first time visitors on the site.The texts on the pages will appear more centerd in smaller devices like mobile and will move horizontally when in bigger devices.


#### General Features 

![Header](documentation/header-largescreens.png)
![Header mobile view](documentation/header-smallscreens.png)
* For all the pages there will be a header consisting of navigation links that allow you to move from one page to another.
* The header element will also have Cafe's logo and name on far left. When hovered over, the cursor becomes pointer and allows you to press the logo and name which then takes you directly to the footer of the page where location , opening times and contact details are shown.  
* For smaller screen the navigation links appear when you press on toggler button that is displayed as 3 red bars top right on the smaller screen.
![Nav links](documentation/navlinks-largescreens.png)
![Nav links](documentation/navlinks-smallscreen.png)
* The navigation links when hovered ontop or when clicked, the background color and color of text changes to #ADD0B3 and white.
* The colors match both in small screens and large screens. 
![Footer](documentation/footer-layout.png)
![Footer small screen](documentation/footer-smallscreen.png)
* The footer contains social media links, opening times, contact details, and location of cafe.
* The maps button takes you directly to google maps.
* The social media links take you directly to facebook and instagram.
* When hovered on the social media links and maps button, the color changes to #ADD0B3, allowing the user to know that they can be clicked on.
---
#### Home Page
This page should attract first time visitors and want them to keep navigating through the website.It has colourful images and 
 a background video . Easy to read information about the cafe's concept and how it works- This is broken down into different blocks so that the information isnt too overwhelming and easy to find. The information is layed out in a way so that the common infomration that the first-time users may be looking for can be found without hassle.It also Shows contact details, Location and opening times as well as social media part as part of the footer.
In addition to header and footer, the home page shows the following:
* A background video with text overlying with a button-When hovered on it turns the same color as the nav links.This button takes you to the main section of home page which tells the user about the concept of cafe and all the information that they might look for when visiting the site. 
* There is a cafe updates feature just below the background video that shows and updates.
* The main section of the page is divided into divs. Each div contains information that would be useful to the user, one of the div also allows you to access event enquiry page directly by allowing you to click on the text that says event enquiry page. 



#### About Page
This page shows how Paint-in cafe came about, information about when it was built, A deep dive into the background story of the owner and even more details about the cafe. 
In addition to the general features of all page , the about page has the following:
* It has a background video with text overlying that specifies that this is the `About` page.
* A section that serves the user information in **bite** size portions. The picture of owner is included(fictional charector) in this section.
#### Cafe Page
This page has the food menu for the cafe. It will also show information that shows that halaal, vegan and gluten free options are available on request.Costs are shown so that the user can be prepared before coming into the cafe. Image of a section of the Cafe is included.
In addition to the general features of all page , the about page has the following:
* It has a background video with text overlying that specifies that this is the `Cafe` page which contains the Cafe Menu.
* It has a section containing 3 blocks that has the menu for the cafe. 
#### Gallery Page
This page has images of paintings, people and food inorder to attract potential customers to visit the cafe.These are placed in the gallery to inspire potential customers to share the cafe website to their family or friends.
In addition to the general features of all page , the about page has the following:
* It has a background video with text overlying that specifies that this is the `Gallery` page which contains the title **Make Memories**.
* It has a section contains all the photos i have saved from [Pexels](https://www.pexels.com/search/paintbrushes/). 
#### Event Enquiry Page
This page has a form that should be filled in if you want to host an event at the cafe or if you are a group of 10 people and more. The form contains name, email address, contact no., type of event, no. of people, special requests and a submit button. 
In addition to the general features of all page , the about page has the following:
* It has a background video with text overlying that specifies that this is the `Event Enquiry` page which contains the title **Host An Event**.
* The main section has 2  divs , one containing information on when and how to send enquiry on the form and the other containing the form itself where certain information needs to be filled in or selected to submit form.
* I did use Onclick function of Javascript to have a pop up message ensuring the user that the message has been sent.

### Future Implementation
* I really wanted to make a slideshow of pictures in the home page and events page but learnt that i would need to use javascript inroder to do so.
* I wanted to make another "Thank you"html page that the submit button in enquiry form redirects you towards instead  of using Onclick function to have a pop up message but i ran out of time to do this. The thankyou.html will display the message "Thank you for submitting our event enquiry form, Our staff will be intouch with you in less than 24hours!"
If this was a real cafe:-
* Id want to implement google reviews in the website so that website visitors would be able to understand the experience from the customer's point of view.
* Change the gallery page outlay to display previous customer's artwork, returning customers will be able to go check out their painting in the gallery.
* Implement a share button inorder for site visitors to share the website with others. 
* I would have liked to include a video of the cafe's concept to help the user understand better.
* I would also include an art class page for customers who actually want to sign up for evening art classes.
* It would also be intersting to have best artwork of the month awards section in the home page.
### Accessibility
These are the ways i have ensured to provide accessibility to users:
* Used HTML semantics.
* Provided navigation links to access other pages.
* Highlighted the navigation link to the current page you are on.
* Ensured Colour Contrast so that the websites are easily readable in light and dark mode.
* Provided alt for images incase images do not load.
* Provided information for icons where no text was provided.
* Provided a submit button in the contact form which will then give out a pop up message. 
* Aria labela and aria properties were implemented.
* Google font "Playfair display" was chosen carefully and i chose the pairing to this font "Open Sans" here [Playfair display pairing](https://typ.io/fonts/playfair_display#:~:text=Playfair%20Display%20is%20a%20serif,Work%20Sans%2C%20Circular%20and%20Georgia.)

## Technologies Used
### Languages Used
HTML and CSS was mainly used to build this website. Javascript was only used for On click function for submit form.
### Frameworks, Libraries and Programs Used
* Balsamiq - For Wireframes
* Gitpod
* GitHub
* Font Awesome
* Google Fonts
* Dev Tools
* Am I Responsive
* Favicon

## Deployment & Local Development

### Deployment
To create a live website of Paint-In Cafe, deployment was done using github pages. The step by step process is shown below:
1. Log in or Sign up to github.
2. Find the repository for this project,Paint-In Cafe.(Can be found under top repositories on the left hand side)
3. Click on Settings link that is displayed above and left to the green gitpod button.
4. Click on Pages link under code and automation in the navigation bar on the left hand side.
5. Under Build and Deployment, click on the branch drop down menu and select main and make sure the select folder drop down is selected on root.
6. Now click save and wait a few minutes.
7. Refresh the page, and the url for your live website will be shown under the heading, GitHub Pages.
8. Deployment is now complete.
### Local Development
#### How to Fork
To fork the Paint-In-Cafe Repository: 
1. Log in or Sign up to github.
2. Find the repository for this project, SooryaGeorge7/Paint-In-Cafe.
3. Click the fork button on top right corner. 
#### How to Clone
To clone the Paint-In-Cafe Repository: 
1. Log in or Sign up to github.
2. Find the repository for this proect, SooryaGeorge7/Paint-In-Cafe.
3. Click on Code button just left to the green gitpod button.
4. Select what you would like to clone with (HTTPS/SSH/GitHub CLI) and copy the link shown below.
5. Open the terminal in your code editor(eg. Gitpod) and change the current working directory to the location you want to use for cloned directory.
6. In the terminal type in "git clone" and paste the link you copied in step 4 above. Press enter.
7. Cloning is now completed.
## Testing
### Automated Testing
#### W3C Validator
#### Lighthouse
#### Wave
### Manual Testing
#### Testing User Stories
#### Full Testing
### BUGS
#### Known Bugs

#### Solved Bugs
* Making a herovideo that also acts as a background video for header. 

## Credits
### Code Used
* [Code used to make hamburger toggler](https://www.codingnepalweb.com/responsive-navigation-menu-bar-html-css/)
* [Learnt how to make shadow to a section here](https://www.w3schools.com/css/css3_shadows_box.asp)
* [Learnt how to make shadow around entire image here for my gallery page poloroid images](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow)
* [Got the code to make gallery to display as a flexbox so that it is responsive here](https://www.youtube.com/watch?v=Trw_9lisYVY)
### Content
### Media
* [Got the home page video from here](https://www.pexels.com/search/videos/watercolor%20paint/)
* [Got all the images for the website from this free image source](https://www.pexels.com/search/paintbrush/)
* [Got the image for favicon here too](https://www.pexels.com/)
### Acknowledgement