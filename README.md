# Flawless Cooking Kids Cookery School 

This is a website for kids cookery classes based in Cork. Complete with enquiry form, downloadable sample recipe and an about section. Flawless Cooking is a fictional cookery school designed for this project. 
This website has been created as the first Milestone project for Code Institute's Full Stack Software Development Diploma. 

## Table of content: 
 1. [Site Goals](#Site-Goals)
    1. [User Goals](#User-Goals)
    1. [Owner Goals](#Owner-Goals)
 1. [UX](#UX)
      1. [Color Contrast](#Color-Contrast)
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
  

## Site Goals:

### User Goals:

This website is designed for a fictional cooking school based in Cork, Ireland. 
The target aduience are parents of kids aged 6 years to 12 years who are showing an interest in cooking and baking. Including a enquiry form which allows parents to contact the school regarding the classes. 
There is also a page that includes an easy recipe that parents can try out at home with their kids before committing to the classes. 

### Owners Goals:

The goals for this site is as follows:
* To provide information to users about kids cookery classes in Cork.
* To provide users with a downloadable sample recipe.
* To allow users gain some information about the teacher.
* Gain more students to the school.
* Invite enquires from parents with children interested in cooking.
* To provide easy to follow recipes that parents can do at home with their kids. 

### Features:


  
## Wireframe:
The wireframe was created using Balsamic and consists of 3 pages, Home, Recipe and About.

#### Home page:

![Home Page](https://user-images.githubusercontent.com/81761397/136006518-960bf764-d74f-4742-8afb-b4c06b9746c5.png)

#### Recipes:

![Recipes Page](https://user-images.githubusercontent.com/81761397/136006678-d10c5a57-75c8-43f0-a0a8-f4459fff6f5e.png)

#### About:

![About Page](https://user-images.githubusercontent.com/81761397/136015563-6cc1cebc-6b6b-4aca-ab49-1b04704b44a8.png)

## Testing:

* Tested navigation bar to make sure all links worked correctly. 
* Tested "Header" logo to make sure it brought me back to the homepage.
* Tested enquiry from to make sure all the required elements were working correctly.
* Tested social media links and email link. 



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

## Valitation:

### **Index.html:**
No errors found 

### **About.html:**
No errors found

### **Recipe.html:**
No errors found

### **Gallery.html:**
No errors found

### **Style.css:**
No errors found

## Accessibility:
![LightHouse Report](assets/readme-images/lighthouse-score.png)

## Deployment:

## Credits:

### Content:

1. The icons used throughout website were taken from [Font Awesome](https://fontawesome.com/)  
1. The logo and heading fonts were taken from [Google Fonts](https://fonts.google.com/)
1. Instructions on who to crop an image was taken from [Digital Ocean](https://www.digitalocean.com/)

### Media:

1. Images for this site were downloaded from [Pexel](https://www.pexels.com/)
1. Video on how to make a flaxseed egg taken from [YouTube](https://www.youtube.com/watch?v=ouUW810R5to)

