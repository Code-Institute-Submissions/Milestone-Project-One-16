# **TinFoT (TeamFight Tactics info)**


## **Milestone project 1: User-Centric Frontend Development - Code Institute**

A website which explains different aspects of the game "Teamfight Tactics".
It is aimed as a free-use project for both new an experienced players looking
for a more convenient overview of information about the game.


## UX

### **Goals:**
* Focus on the essential information with the assumption the user 
    already has an understanding of the rules of the game.

* Make it quick to navigate, allowing users to find the specific
information they were looking for .

* To make the website as aesthetically pleasing as possible, encouring return visits
by making regular visits an enjoyable and positive experience.

* To make the site stand out from other websites which fulfill similar 
roles.

### **User Stories**

I asked a number of people in the gaming community what 
they look for in a website like mine.

>Game wiki websites are often cluttered with information. It makes for
interesting reading if I'm in the mood but usually I want a basic bit of information
not the whole game's lore (**Content**)

> - Coburn Martin

>I wish some gaming websites were a bit brighter. Every site is so gloomy. (**Aesthetic**)

> - Ebba Gärdekrans

>I am usually looking at information whilst simultaneuosly playing the game 
so i want to find the information I'm looking for quickly so I can get back
to actually playing the game. (**Accessibility**)

> - Nancy Oliveira

### **Strategy**

The aim was to create a bright and colourful website which only presented the 
user with most essential information and to make it quick and easy to reach 
any specific bit of information. 

### **Scope**

A website like this would normally require a database. With that in mind the 
website must be designed as a demo which shows off all the aspects that the full 
website would contain. This means that any repition of templates should be avoided.

### **Structure**

Quick navigation is essential to this project. All of the sections are on the same page
and the navigation bar sticks to the top of the screen. Only by clicking on the "read more"
link in the champions section will take the user away from the main page. This means only 
the most essential information is displayed. 

### **Skeleton**

Using figma the following wireframes were made:

https://github.com/OGMyst/Milestone-Project-One/blob/master/mockups/Desktop.pdf

https://github.com/OGMyst/Milestone-Project-One/blob/master/mockups/Phone.pdf

It was decided that the "Origin" and "Class" sections should be removed as the information
they contained could be put into the champion section. In addition, the patch notes now link 
to the official patch notes on the Teamfight Tactics website.

### **Surface**

The light colours, in particular the heavy use of blue, brightens the website making it more
appealing and differentiates the website from similar sites. The "Lobster" font was chosen
to be used for the headers for its curly and thick style. This adds to the more friendly, 
less formal website that users are accustomed to.

### **Technologies**

    HTML - To create a basic site
    CSS - To create a nice style and to stand-out
    Bootstrap - To improve responsiveness
    Figma - To create a wireframe


## Features

The site uses a parallax scrolling effect in CSS which adds an extra layer and gives a smoother
scrolling experience. For phone screen sizes the navbar changes into a collapsible burger icon 
freeing up space. The main page contains all the essential information and the navbar links to
each section on the page. This eliminates load times for everything apart from the champion 
specific page, allowing the user to find the relevant piece of information as quickly as possible.

### Features Left to Impliment

Should the site gain access to a database it would open the possibility to include in-depth
champion information pages for all the champions in the game. On the main page this would mean 
all eighty three champions would be present. To prevent the main champion section being very 
long, the desciptions would be put inside a box which only appears when clicked on. The thirteen
items and their combinations would be collapsed into dropdown boxes to maintain accessibility.


## Testing

All links work both within the site and to the external patch notes. All "Read More" links lead 
to the same champion page. 

The site is responsive over different screen sizes with custom layouts where appropriate. The site 
has been tested on Mozilla Firefox, Google Chrome and safari and works as intended.The site was 
tested on an android phone, Iphone, tablet, Ipad, laptop, Macbook and desktop. The colour styles 
appear more vibrant on different screens but all site functions work as intended. 

### **Bugs**

The following tests have been used to ensure proper site functionality:

* GTmetrix: To test on website loading times
* W3C HTML Validator: This validator checks the markup validity of Web documents in HTML.
* W3C CSS Validator: This validator checks the markup validity of Web documents in CSS.


## **Deployment**

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update 
automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, 
the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting the link into 
your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

## **Credits**

### **Content**

All content on this site were written by me.

### **Media**

All photos were taken from tftactics.gg and wallpapercave.com

## **Acknowledgements**
The Parallax Scrolling effect was found on w3schools.com link (by mentor advice)

[tftactics.gg](https://tftactics.gg/item-builder) This site gave inspiration for
the layout of the item section.
