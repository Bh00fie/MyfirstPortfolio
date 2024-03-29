# My First Online Portfolio

## Introduction

A portfolio of work can showcase your skills and talents to employers looking to fill a part-time or full-time position. An effective portfolio highlights your strongest work as well as the thought processes behind it.

In this challenge, I am going to make a personal portfolio using all the knowledge gained in the last week, this include, flexbox, grid, Responsive Web Design, Root and the Hover effect. 

My goal would be to create a website that changes design at three different widths, `Full Screen`, `980px` and `789px` as well as use Grid efficiently while ensuring the layout of the website is consistent and impressive to whoever is going to check your website.

I was given a specific layout to copy, the following: 

### - Width: Full Screen (above 980px) 
![Full Width](/Images/Solution/LargeScreen.png)
### - Width: between 789px and 980px
![Medium Width](/Images/Solution/Medium.png)
### - Width: Below 789px
![Small Width](/Images/Solution/small.png)

The website must check these criteria: 
- When the page is loaded the page presents your name, a recent photo or avatar, and links to sections about you, your work, and how to contact you.
- When one of the links in the navigation is clicked then the UI scrolls to the corresponding section.
- When viewing the section about your work then the section contains titled images of your applications.
- When presented with your first application then that application's image should be larger in size than the others.
- When images of the applications are clicked then the user is taken to that deployed application.
- When the page is resized or viewed on various screens and devices then the layout is responsive and adapts to my viewport.


---

## Description

I have started by creating a plan to follow which allowed me to follow a clear path and not try to do "some here some there". 
The plan was the following:
- Wireframe Model
- Rough HTML
- Rough CSS
	- Root for different colors
	- Header using flex
	- About me using flex
	- Work using Grid
	- Contacts using Flex
- Cleaned and fixed remaining HTML Code
- Cleaned and fixed remaining CSS code (added hover effects for example)
- Responsive design at 980px
- Responsive design at 789px
- Commented
- Pushed code and deploy webpage on GitHub

The use of Grid was composulary, the `grid` could have been used in two ways, you could have make a main grid including everything under `page-wrapper` and nest another `grid` for the `work` section. Or, you could create use `display: flex` for every title or the right side of the page and make a `grid` for the work section.

![Grid](/Images/grid.jpg)

One of the criteria for this Portfolio as well for this assignment was to create an hover effect when going on top of the image of a project. 
This was done by creating the hyperlink element `a` and giving a class to create a box to cover the image, this was put on top using index-z. The transparency was set to 0.5 by default and the hoper effect simply makes the box transparent so the link can be still clicked.

![Hover Effect](/Images/hover.gif)

The responsiveness of this website was also crucial, indeed different styling can be seen in the `Final Results` Section.

The update website can be found at: abhinandanthour.com

---

## Final Results at different screen sizes

### - Width: Full Screen (above 980px) 
![Full Width](/Images/Solution/Myownwebsite/FullWidthOwnWebsite.png)
### - Width: between 789px and 980px
![Medium Width](/Images/Solution/Myownwebsite/980pxOwnWebsite.png)
### - Width: Below 789px
![Small Width](/Images/Solution/Myownwebsite/789pxOwnWebsite.png)

---

## License

MIT Licence

---

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
