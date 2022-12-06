# My First Online Portfolio

## Introduction

In this challenge, I am going to make a personal portfolio using all the knowdledge gained in the last week, this include, flexbox, grid, Responsive Web Design, Root and the Hover effect. 

My goal would be to create a website that changes design at three different width, xxxpx, xxxpx and xxxpx as well as usign grid efficiently while unsuring the layout of the website is consistent and good.

I was given a specific layout to copy, the following: 

- Full Screen
- Mid Screen
- Small Screen

## Description

I have started with creating a plan to follow which allowed me to follow a clear path and not try to do "some here some there". The plan was the following. 
- Wireframe Model
- Rough HTML
- Rough CSS
	- Root for different colours
	- Header using flex
	- About me using flex
	- Work using Grid
	- Contacts using Flex
- Cleaned and fixed remaining HTML Code
- Cleaned and fixed remaining CSS code (added hover effects)
- Responsive design at 980px
- Responsive design at 789px
- Commented
- Pushed code and deploy webpage on GitHub

----
stuff from the assignment page
----

The update website can be found at: https://bh00fie.github.io/Horiseon-SEO-and-Digital-Marketing/

## Final Results at different screen sizes

- Full widht
- Medium width
- Small width

Various changes were made to the code to make it more accessible and efficient. 

Starting from the top of the HTML file, the title of the website has changes from "webpage" to "Horiseon - SEO and Digital Marketing experts" which is the customer name:
![Old Title](/assets/images/Title-old.jpg) vs ![New Title](/assets/images/Title-new.jpg)

Moving to the body, previous developer did not use comments and a semantic structure which I have implemented:
![Without Semantic Code](/assets/images/Semantic-old.jpg) vs ![With Semantic Code](/assets/images/Semantic-new.jpg)
In the image above of the old code, it can be also seen that `alt` attributes were not used, fundamental to have an accessible website.
Comments were also missing which helps future developer as well as the customer to understand what each line means and allows to make it easier when upgrading or making any changes to the website.

CSS Stylesheet was also missing comments:
![Old CSS Comments](/assets/images/Comments-old.jpg) vs ![New CSS Comments](/assets/images/Comments-new.jpg)
These are fundamental to make the code clearer and keep track of changes or features.

As the HTML was changed to a sementic structure, many `div` and `class` were taken out such and replaced, a clear example is the navigation bar:
![Old Nav Bar](/assets/images/Nav-old.jpg) vs ![New Nav Bar](/assets/images/Nav-new.jpg)

Also, the stylesheet was full of unnecessary repetition which could slow the webpage done and makes it difficult to make changes in the feature so classes with the same style have been grouped together:
![Old Code with Repetitions](/assets/images/Repititions-old.jpg) vs ![Old Code without Repetitions](/assets/images/Repititions-new.jpg)
By doing so the code went from 201 lines to 128 keeping the webpage look and functionality the same.

As the footer is not a class anymore it was replaced with its own element:
![Old Footer](/assets/images/Footer-old.jpg) vs ![New Footer](/assets/images/Footer-new.jpg)

The final website looks like the following:
![Updated Webpage](/assets/images/Final-website.png)

## Credits

Horiseon webpage and challange taken from: edX 16 week bootcamp Front End Developer on [GitLab] (https://git.bootcampcontent.com/uk-edx-16-week/UK-VIRT-FE-PT-11-2022-U-LOLC)


## License

MIT Licence

---

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
