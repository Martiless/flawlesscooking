# Flawless Cooking Cookery School 

This website is designed for a fictional cooking school based in Cork, Ireland. It is complete with an enquiry form for potential clients to get in contact with the school, an about section to tell people a little about the teacher and a gallery page which shows images of past students to the school. There is also a recipes page with a sample brownie recipe. This page also cotains a downloadable verison of the recipe and a video on how to make a flaxseed egg for anyone who would like to make a vegan friendly version of the brownie. 
This website has been created as the first Milestone project for Code Institute's Full Stack Software Development Diploma. 

![Am I Responsive](assets/readme-images/am-i-responsive.png)

### View the live website [here]()
***
## Table of content: 
 1. [Site Goals](#Site-Goals)
 1. [UX](#UX)
      1. [User Goals](#User-Goals)
            * [Target audience](#Target-audience)
            * [User Stories](#User-Stories)
      1. [Color](#Color)
      1. [Font](#Font)
      1. [Images](#Images)
 1. [Features](#Features)
      1. [General](#General)
      1. [Home page](#Home-page)
      1. [About](#About)
      1. [Recipes](#Recipes)
      1. [Gallery](#Gallery)
 1. [Wireframe](#Wireframe) 
 1. [Testing](#Testing)
 1. [Bugs](#Bugs)
 1. [Validation](#Validation)
 1. [Accessibilty](#Accessibilty)
 1. [Deployment](#Deployment)
 1. [Credits](#Credits)
      1. [Content](#Content)
      1. [Media](#Media)
      1. [Code](#Code)
***
  

## Site Goals:

The goals for this site is as follows:
* To provide information to users about kids cookery classes in Cork.
* To provide users with a downloadable sample recipe.
* To allow users gain some information about the teacher.
* Gain more students to the school.
* Invite enquires from parents with children interested in cooking.
* To provide easy to follow recipes that parents can do at home with their kids. 

## UX:

An initial [Wireframe](WIREFRAME.md "Link to Wireframe screenshots") was created using [Balsamiq](https://balsamiq.com/)  
This inital drawing had 3 pages *Home, About and Recipe* but since then has become a 4 page site with a gallery page showing examples of previous children who have been taught at the school. 


## User Goals:

 ### Target Audience:

* Parents of children aged 6 - 12 years
* Grandparents and guardians of children aged 6 - 12 years

### User stories:
#### New User:  
* As a new user I am looking to find information regarding cooking classes for kids.  
* As a new user, I am looking to contact the school.  
* As a new user, I would like to find out more about the person who will be teaching my child.  
* As a new user, I would like to see pictures of past students of the school.  
* As a new user, I would like to get an idea of the types of recipes my child will be learning.  

#### Returning User:
* As a returning user, I would like to find out if there are any new recipes available to download.
* As a returning user, I would like to see if there are any new class times added.
* As a returning user, I would like to see if any new class photos have been added.

### Color: 
In order to create a visually appealing website but also an 

### Font:

### Images:

***
[Back to top](#Flawless-Cooking-Cookery-School)  
  

## Features:

### General:

### Home page:

### About:

### Recipes:

### Gallery: 
***
[Back to top](#Flawless-Cooking-Cookery-School)  

## Testing:

### Home page:

* Each button on the navigation bar were tested to make sure they brought you to the correct place.  
* The logo in the header was tested to make sure you return to the home page when it is clicked on.  
* Each social media icon in the footer was tested to make sure they not only opened in the correct social media pages but that they also opened in a new tab.
* The email icon in the footer was tested to make sure it opened correctly
* Each field of the enquiry form was tested to make sure if it was empty a warning popped up to let the user know the field was required and that the submit button worked correctly
      * The submit button currently refresh the homepage when clicked.  

### About page:
* Header and footer as above.  
* Links in the experience section were tested to make sure they both brought you to the right websites but also opened in new tabs.

### Receipes page: 
* Header and footer as above.  
* Link in the ingredients was tested to make sure it directs users to the video at the bottom of the page.
* Download button was tested to make sure it opened a downloadable PDF in a new tab for users.
* Video was tested to make sure it played.

### Gallery page:
* Header and footer as above.

### Responsiveness:
All pages were checked using Google Dev tools to make sure they were desktop, tablet and mobile compatable.  

### Browsers:
This site was tested to make sure it loaded correctly on 
1. Google Chrome 
1. Microsoft Edge
1. Mozilla Firefox
***

## Bugs:
1. Font Awesome fonts are copied into the code but when the webiste is loaded are not showing up. 
      1. I had forgotten to add the Font Awesome source code to the footer section of each page.
1. Main image not loading when page refreshed.
      1. Looked at source to make sure I was using the correct syntax, I had added in an extra full stop. Removing this extra full stop solved my issue.
1. Second image not cropping correctly.
      1. Instead of using the same method as the header image, I inserted the second image in the html as a < img > tag and styled it using CSS
1. Image and text in "Middle" would not wrap for me. 
      1. I tried a number of things including rewriting the code, troubleshooting to see if I had used the wrong code in the first place and eventually contacted the Code Institute tutors to see if I could get a better understanding as to why this was not working for me the way I wanted it to. 
      1. After speaking with a tutor I was able to see that I had to take a closer look at my margins and padding to allow both the image and text fit side my side in the designated area.
1. About page would not load correctly after adding the media queries to the pagea.
      1. Used Google Dev Tools to try and fix the code. The code was in GitPod but not appearing in Dev tools
      1. Tried hard refreshes
      1. Tried rewritting the code
      1. Finally contacted the Code Institute tutors who helped me see that I was missing some closing brackets from previous media queries that was causing the code from the About page to be overwritten. Once these bracets were closed the page loaded correctly.
1. When I was making my site responsive pages recipe page started to load wrong, i.e the footer was above the middle section of the page. 
      1. I was having a really hard time with this one as I had double and triple checked all my code in GitPod and also used Google Dev tools and couldn't see any problem. I eventually decided to used the Tutor service where one of the tutors explained to me about flex and flex-box as a way of displaying content instead of floats. By changing the images css from a float to a flex corrected the issue I was having.
1. Navigation bar was not responding correctly when viewed in tablet form. 
      1. Used Google Dev Tools to try differnt methods of getting the page to work.
      1. Eventually discoverd that the margin wasn't set correctly as it was still set to the default margins.
1. While generating the LightHouse Report I was getting an error due to some code that was appearing at the end of each of my .html files, but that I had not written nor was it appearing in GitPod
      1. I went through all my extension I have installed on Google Chrome and discovered that an app was inserting code into the site while in the preview 8000 mode.
      1. I disabled the app and ran the Lighthouse report again which came back without the same feedback. 
***
## Valitation:

See screenshot to W3C validator and Jigsaw CSS validator [here](VALIDATION.md "Link to validation screenshots")

### **Index.html:**
No errors found. 

### **About.html:**
No errors found

### **Recipe.html:**
No errors found

### **Gallery.html:**
No errors found

### **Style.css:**
No errors found
***
## Accessibility:
![LightHouse Report](assets/readme-images/lighthouse-score.png)
***
## Deployment:
***
## Credits:

### Content:

1. The icons used throughout website were taken from [Font Awesome](https://fontawesome.com/)  
1. The logo and heading fonts were taken from [Google Fonts](https://fonts.google.com/)
1. Instructions on who to crop an image was taken from [Digital Ocean](https://www.digitalocean.com/)

### Media:

1. Images for this site were downloaded from [Pexel](https://www.pexels.com/)
1. Video on how to make a flaxseed egg taken from [YouTube](https://www.youtube.com/watch?v=ouUW810R5to)

### Code:

1. I used various different coder forums at times when I had difficulty with aspects of the code. The use of sites such as [W3 Schools](https://www.w3schools.com/) and [Stack Overflow](https://stackoverflow.com/) were hugely helpful, as well as coding community sites like [Site Point Community](https://www.sitepoint.com/community/)  
Any code taken from these sites were edited to site the needs of this site. 
1. CSS Code for image on recipe page was help with by the tutors from Code Institute  