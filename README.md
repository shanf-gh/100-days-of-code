# #100DaysOfCode Log - Round 1 - Fabien

The log of my #100DaysOfCode challenge. Started on [January 15, Monday, 2017].

### Day 011: January 25, 2018
**Today's Progress**:
1. [fCC] Made the design for the JS Calculator

**Thoughts**
- [fCC] Started the JS calculator project. 
- Started trying with flexbox but it was hard to spread the divs of the input panel equally. [Flexbox free course](https://scrimba.com/g/gflexbox)
- Used CSS grid to space the different elements, in particular the input panel. [Grid free course](https://scrimba.com/c/cbVn4t4)

**Link(s) to work**
1. [fCC JS Calculator](https://codepen.io/X140hu4/pen/goNxpa?editors=0100)

### Day 010: January 24, 2018
**Today's Progress**:
1. [Portfolio] Finished first version

**Thoughts**
- [Portfolio] Finished a first version of the portfolio in English. The contact form is missing its functionality but I couldn't make it work to make a post request. 
- Added color on hover of logos
- Added skills section. I used font awesome 5 as it had icons instead of fa4
- Added actual portfolio content

**Link(s) to work**
1. [Portfolio](https://github.com/X140hu4/X140hu4.github.io)

### Day 009: January 23, 2018
**Today's Progress**:
1. [Portfolio] Worked on portfolio's sections

**Thoughts**
- [Portfolio] Made a hero section, populated and styled it. Found a trick for the internal link from navbar to section of the page. The problem was that when clicking on "My work", the page would go below the Portfolio header. The trick I found and was satisfied with was to have a `<a></a>` tag with a class of anchor with certain properties, including an negative vertical offset.
Added the about section, work in progress. I would need to add the skills section too at some point but I had some issues with the logos having different sizes... I think I would need to resize them first for the screen size and file size so that they don't use too much data on load.

**Link(s) to work**
1. [Portfolio](https://github.com/X140hu4/FCC/tree/master/1.%20Portfolio/Ver_2018_01)

### Day 008: January 22, 2018
**Today's Progress**:
1. [Portfolio] Worked on portfolio's
2. [fCC] Helped campers on gitter and fCC's forum

**Thoughts**
- [Portfolio] I had some trouble with the different navbars and how they should be nested. Managed to get a basic navbar with all the elements I wanted and responsiveness thanks to bootstrap 4.

**Link(s) to work**
1. [Portfolio](https://github.com/X140hu4/FCC/tree/master/1.%20Portfolio/Ver_2018_01)

### Day 007: January 21, 2018
**Today's Progress**:
1. [WebDevBootcamp] Finished Bootstrap

**Thoughts**
- [WebDevBootcamp] 771 (Forms and inputs) 781 (End of Bootstrap chapter)

**Link(s) to work**
No links today!

### Day 006: January 20, 2018
**Today's Progress**:
1. [WebDevBootcamp] Started Bootstrap

**Thoughts**
- [WebDevBootcamp] Finished 547 (Specify and the cascade) 771 (Forms and inputs)

**Link(s) to work**
No links today!

### Day 005: January 19, 2018
**Today's Progress**:
1. [WebDevBootcamp] Started Intro to CSS (Refresh)

**Thoughts**
- [WebDevBootcamp] Finished 435 (Form exercise) to 547 (Specify and the cascade)

**Link(s) to work**
No links today!

### Day 004: January 18, 2018
**Today's Progress**:
1. [Portfolio] Set up of folders
2. [WebDevBootcamp] Refresh HTML knowledge

**Thoughts**
- [Portfolio] Starting setting up the folder structure and the files with some html and styling. I will go with bootstrap to quicken the development process
- [WebDevBootcamp] Started at 317 (Basic tags) stopped at 435 (Form exercise)

**Link(s) to work**
1. [Geckos-36 repo](https://github.com/chingu-voyage3/geckos-26)

### Day 003: January 17, 2018
**Today's Progress**:
1. [geckos-26] Finished CRUD routes
2. [Portfolio] Finished initial wireframing

**Thoughts**
- [Geckos] Issues encountered:
    - Delete route: I wanted to delete the list but also the related cards. The cards' ids are in a cards property of List. I needed to get the list first, then get the cards array and iterate through the cards and delete them. Once the cards are delete the list is deleted. When the cards are deleted their reference in the cards array of list are not.
- [Portfolio] Finished initial wireframing for a one page page. Another idea would be to have the body show only the part selected in the navbar instead of having everything available to scroll?

**Link(s) to work**
1. [Geckos-36 repo](https://github.com/chingu-voyage3/geckos-26)


### Day 002: January 16, 2018
**Today's Progress**:
1. [geckos-26] Worked on create route for new list
2. [Portfolio] Used Evolus Pencil to start wireframing the portfolio site

**Thoughts**

- [Geckos] Issues encountered trying to pass data around for Create List:
    - Get data from the form: Used ref on the input field
    - Access ref from parent component: pass 'hook' via props to the child to assign value to variable in parent
    - post a json request: added a header specifying content-type to be json and assigned JSON.stringify(data) to the body.
Used the article ["CRUD in React and Express (MySQL)"](https://medium.com/@avanthikameenakshi/crud-react-express-99025f03f06e) to kickstart working on fetch post.
[Portfolio] Hands on pencil to start wireframing the portfolio.


**Link(s) to work**
1. [Geckos-36 repo fetchPost branch](https://github.com/chingu-voyage3/geckos-26)

### Day 001: January 15, 2018
**Today's Progress**:
1. [geckos-26] Merged candy's card moving branch. Closed PR and deleted branch.

**Thoughts**

It is a big mess when there are conflicts... I had to loose the props in the subcomponents Lists and Cards.
Also capitalization on file name seems to throw github off when making comparisons between files... So defintely need to be all aligned on no capitalization in name file, and no spaces.


**Link(s) to work**
1. [Geckos-36 repo](https://github.com/chingu-voyage3/geckos-26)
