# Sprint Challenge: User Interface and Git

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied semantic HTML, CSS fundamentals, git, and responsive design. In your challenge this week, you will demonstrate proficiency by creating a fully responsive website that has some missing HTML elements as well as CSS specificity problems that need to be solved.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, git, and responsive design.

> You have **three hours** to complete this challenge. Plan your time accordingly.


## Introduction

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and make your page responsive for mobile. You will be working with a pre-existing web page, allowing you to get a taste of what it is like to inherit code from someone else, as will regularly happen on the job.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home page and mobile version. 

 [Click here for home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)
 
 [Click here for tablet example](design/tablet.png)


[Click here for mobile example](design/mobile.png)

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. If you were to describe semantic HTML to the next cohort of students, what would you say?  

    Semantinc HTMl is HTML that gives meaning to the content of the page. It helps to make it readable to both humans and machines which helps to make your website more accessible.

2. What are the 4 areas of the box model?
    1. content
    2. padding 
    3. border
    4. margin 

3. While using flexbox, what axis does the following property work on: ```align-items: center```?  

    The cross axis. By default the cross axis is vertical. 

4. Explain why git is valuable to a team of developers.  

    It allows the team to work on the same area of code at the same time and prevents merge issues when trying to put the code together. Git also helps to keep a timeline of all the changes made in the code. This timeline allows a team to revert back to a previous working version if needed. 

5. Define mobile-first design in your own words.  

    Mobile-first design is designing the webpage by thinking of the smallest screen first and scaling up to the largest screen.

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Instructions

### Task 1: Project Set Up

- [ ] Create a forked copy of this project
- [ ] Add your team lead as collaborator on Github
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!)
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.
- [ ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly
- [ ] Push commits: git push origin `<firstName-lastName>`

### Task 2:  Minimum Viable Product

Your finished project must include all of the following requirements:

#### Home Page

[Review the provided design files](/design). Notice the navigation and header images are missing in the starter code.

* [ ] Build the HTML and CSS to create the missing navigation and header
* [ ] Link the `About` navigation item to an about.html page (you'll also need to create `about.html`)
* [ ] Make your design responsive such that it is accessible on mobile(500px) and tablet(800 px) and matches the [mobile](design/mobile.png) wireframe
*  Add responsive breakpoints to your code by using media queries

You will also notice there are 10 boxes on the home page that need background colors.  Use this list below to correctly style each box:

* [ ] box1: `teal`
* [ ] box2: `gold`
* [ ] box3: `cadetblue`
* [ ] box4: `coral`
* [ ] box5: `crimson`
* [ ] box6: `forestgreen`
* [ ] box7: `darkorchid`
* [ ] box8: `hotpink`
* [ ] box9: `indigo`
* [ ] box10: `dodgerblue`

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

### Task 3: Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Build a page of your choosing from the navigation items.  Come up with content and images that fit the theme.  
* [ ] Introduce CSS animations to your site.
* [ ] Build a contact page and create a form with several inputs of your choosing

## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

## Submission format

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your team lead as a reviewer on the pull-request
- [ ] Your team lead will count the project as complete by merging the branch back into master
