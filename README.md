### Terms and agreements

By starting this project, you agree to the guidelines of the Trybe Code of Ethics and Conduct and the Student Handbook.

# Welcome to the Lessons Learned project repository!

You already use GitHub daily to develop exercises, right? Now, to develop the projects, you must follow the instructions below. Pay attention to each step and, if you have any questions, send them to us via _Slack_! #vqv 🚀

Here you will find details on how to structure the development of your project from this repository, using a specific branch and a _Pull Request_ to place your codes.

---

## SUMMARY

- [Skills](#skills)
- [Deliverables](#deliverables)
   - [What should be developed](#what-should-be-developed)
   - [Development](#development)
   - [Delivery date](#delivery-date)
- [Instructions for submitting your project](#instructions-for-delivering-your-project)
   - [Before starting to develop](#before-starting-to-develop)
   - [During development](#during-development)
- [How to develop](#how-to-develop)
   - [Linter](#linter)
   - [Automatic Evaluator](#automatic-evaluator)
- [Requirements](#requirements)
   - [Tips](#tips)
   - [List of requirements](#list-of-requirements)
     - [1. Add a specific background color to the page](#1-add-a-specific-background-color-to-the-page)
     - [two. Add a topbar with a title](#2-add-a-topbar-with-a-title)
     - [3. Add a photo of yourself to the page](#3-add-a-photo-of-yourself-to-page)
     - [4. Add a list of lessons learned to the page](#4-add-a-list-of-lessons-learned-to-page)
     - [5. Create a list of lessons you still want to learn for the page](#5-create-a-list-of-lessons-you-still-want-to-learn-for-the-page)
     - [6. Add a footer to the page](#6-add-a-footer-to-the-page)
     - [7. Insert at least one external link on the page](#7-insert-at-least-one-external-link-on-page)
     - [8. Create an article about your learning](#8-create-an-article-about-your-learning)
     - [9. Create a section that tells a passage about your learning](#9-create-a-section-that-tells-a-passage-about-your-learning)
     - [10. Apply HTML elements according to the meaning and purpose of each of them](#10-apply-html-elements-according-to-the-sense-and-purpose-of-each-of-them)
   - [Bonus](#bonus)
     - [11. Test the semantics of your page if it is approved by the CodeSniffer website](#11-test-the-semantics-of-your-page-is-approved-by-the-codesniffer-site)
     - [12. Add a table to the page](#12-add-a-table-to-page)
     - [13. Use the Box model](#13-utilize-o-box-model)
     - [14. Change attributes related to fonts](#14-change-attributes-related-to-fonts)
     - [15. Position your article and the learnings section next to each other](#15-position-your-article-and-the-learnings-section-next-to-each-other)
- [After finishing development](#after-finishing-development)
- [Reviewing a pull request](#reviewing-a-pull-request)
- [Final Notices](#final-notices)


## Skills

In this project, you will be able to:

* Use _HTML_ to build WEB pages.
* Use semantic _HTML_ to make your page more accessible and better ranked.
* Use _CSS_ to add style and position elements.

---

## Deliverables

To deliver your project you must create a Pull Request in this repository.

Remember that you can consult our content on
[Git & GitHub](https://app.betrybe.com/course/fundamentals/git-github-e-internet/git-github-o-que-e-e-para-que-serve/82dcab41-249a-4738- 8920-f0eb2cb91d1c/dinamica-de-controle-de-version/4cbb1980-92f0-4663-9121-dbc0f8d207a7?use_case=calendar) whenever you need it!

---

## What should be developed

You will develop a website that contains a series of information about what you have learned here at Trybe over the last three blocks. Your website must have positioned and stylized elements and, in addition, it must contain appropriate semantics so that it is accessible and better ranked.


## Development

You must develop an HTML page styled with CSS.

Through this application, it will be possible to perform HTML code construction, positioning and CSS styling.

## Delivery date

   - It will be `1` day of the project.
   - Delivery date for final evaluation of the project: `18/05/2022 14:00`.

---

## Instructions for submitting your project

### Before you start developing

1. Clone the repository
   * `git clone git@github.com:tryber/sd-023-b-project-lessons-learned.git`.
   * Go to the repository folder you just cloned:
     * `cd sd-023-b-project-lessons-learned`

2. Install dependencies and initialize the project
   * Install dependencies:
     * npm install

2. Create a branch from the `master` branch
   * Check that you are on the `master` branch
     * Example: `git branch`
   * If not, switch to the `master` branch
     * Example: `git checkout master`
   * Now, create a branch where you will store your project's commits
     * You must create a branch in the following format: `firstname-lastname-project-name`
     * Example: `git checkout -b maria-soares-lessons-learned`

3. Create the files you will need to develop in the root of the project:
   * Verify that you are at the root of the project
     * Example: `pwd` -> the return will be something like _/Users/maria/code/**sd-023-b-project-lessons-learned**_
   * Create index.html and style.css files
     * Example: `touch index.html style.css`

4. Add changes to Git _stage_ and `commit`
   * Check that the changes are not yet in _stage_
     * Example: `git status` (new files should appear listed in red)
   * Add the new file to Git _stage_
       * Example:
         * `git add .` (adding all changes - _that were in red_ - to the Git stage)
         * `git status` (files should appear listed in green)
   * Make the initial `commit`
       * Example:
         * `git commit -m 'starting the project. LET'S GO WITH EVERYTHING :rocket:'` (making the first commit)
         * `git status` (a message like _nothing to commit_ should appear)

5. Add your branch with the new `commit` to the remote repository
   * Using the previous example: `git push -u origin maria-soares-lessons-learned`

6. Create a new `Pull Request` _(PR)_
   * Go to the [GitHub repository](https://github.com/tryber/sd-023-b-project-lessons-learned/pulls) _Pull Requests_ page
   * Click on the green _"New pull request"_ button
   * Click on the _"Compare"_ checkbox and choose your branch **carefully**
   * Click the green _"Create pull request"_ button
   * Add a description for the _Pull Request_, a clear title that identifies it, and click the green _"Create pull request"_ button
   * **Don't worry about filling out anything else for now!**
   * Go back to the [repository's _Pull Requests_ page](https://github.com/tryber/sd-023-b-project-lessons-learned/pulls) and check that your _Pull Request_ is created

---

### During development

* Commit changes you make to the code regularly

* Remember to always after one (or a few) `commits` update the remote repository

* The commands you will use most frequently are:
   1. `git status` _(to check what is in red - out of stage - and what is in green - on stage)_
   2. `git add` _(to add files to the Git stage)_
   3. `git commit` _(to create a commit with the files that are in the Git stage)_
   5. `git push -u branch-name` _(to push the commit to the remote repository the first time you `push` a new branch)_
   4. `git push` _(to push the commit to the remote repository after the previous step)_

---

## How to develop

### Linter

To guarantee the quality of your code in order to make it more readable, easier to maintain and following good development practices, we use the `ESLint` linter in this project. To run the linter locally in your project, run the command below:

```bash
npm run lint:styles
```

⚠ **IN THIS PROJECT STYLELINT WILL NOT BE EVALUATED. YOU CAN RUN THE TEST LOCALLY AND MAKE CORRECTIONS IF YOU WISH!** ⚠

After cloning the project, you must create the **index.html** and **style.css** files that will contain your HTML and CSS code, respectively. Note that your files **must** have these names for your project to be tested correctly by the automatic evaluator.

You are free to add other files if necessary. If you have any questions, contact the Instructor who accompanies you.

Remember that your page must contain adequate semantics and to do this, check if your page is approved by [CodeSniffer](https://squizlabs.github.io/HTML_CodeSniffer/).


### Automatic evaluator

* Your project requirements are automatically evaluated, using a screen resolution of `1366 x 768` (1366 pixels wide by 768 pixels high).

* ⚠️ It is recommended to develop your project using the same resolution, by installing [this plugin](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh?hl=en) from `Chrome` to make it easier the resolution setting. ⚠️

* Pay attention to the size of the images you will use in this project. **Do not use images larger than _500Kb_.**

* ⚠️ Use a tool [like this](https://picresize.com/pt) to resize images. ⚠️

* If the evaluation fails with an error message similar to `[409:0326/130838.878602:FATAL:memory.cc(22)] Out of memory. size=4194304`, the images you are using are probably too large. Try resizing them to a smaller size.

To check whether your evaluation was computed successfully, you can check the **evaluator execution details**.

* On your _Pull Request_ page, above the "merge button", search for _**"Evaluator job"**_ and click on the _**"Details"**_ link;

* On the page that will open, look for the line _**"Cypress evaluator step"**_ and click on it;

* Analyze the results from the message _**"(Run Starting)"**_;

* If you have questions, consult [this video](https://vimeo.com/420861252) or look for the instructors.

To run the automatic evaluator locally in your project, run one of the commands below:

```bash
npm test
```

***or***

```bash
npm run cypress:open
```

After executing the command above, a browser window will open and then just click on the name of the test file you want to run (*project.spec.js*, or *bonus.spec.js*), or to run all tests click on *Run 2 integration specs*

You are free to add new behaviors to your project, whether in the form of improvements to proposed requirements or new functionalities, **as long as such additional behaviors do not conflict with the proposed requirements**.

* You can do more than asked, but never less.

* **Nothing beyond what is requested in the requirements will be evaluated**. _This is an opportunity for you to exercise your creativity and experiment with the knowledge you have acquired._

---

## Requirements

### Tips

To put your page on [GitHub Pages](https://pages.github.com/), there is no need to remove the content that is already there, you can just add this new page. To do this, all content of this project must be placed in a folder `/projetos/lessons-learned`.

### List of requirements

⚠️ Read them carefully and follow exactly what is asked. In particular, **pay attention to the names of _ids_ that some elements of your project must have**. ⚠️

Failure to comply with a requirement, in whole or in part, will impact your assessment.

---

### 👀Important notes:

* Remember that as developers we must do research and mine results to help understand the subject. Therefore, to solve the project requirements, it is inevitable and encouraged that research be carried out in a wide variety of sources (course, course videos, google, youtube, etc.) always taking care to use "reliable" sources in Internet searches, such as :
  
   * [Javascript.com](http://javascript.com/)
  
   * [W3Schools](https://www.w3schools.com/js/default.asp)
  
   * [MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
  
   * [StackOverflow](https://pt.stackoverflow.com/questions/tagged/javascript)
  

### 1. Add a specific background color to the page

Have background color: rgb(253, 251, 251)

**What will be checked:**

- Have background color: rgb(253, 251, 251)

### 2. Add a top bar with a title

The bar must have the ID "header" and must be fixed at the top of the page with the top property having **0**. The title must be inside the bar and be an **h1** element with ID "title".

**What will be checked:**

- The bar has the ID "header"
- The top bar must be fixed at the top of the page, read more about it [here](https://www.w3schools.com/css/css_positioning.asp).
- The bar must have the **top** property having the value `0`
- The title must be inside the bar and have the ID "title", in addition to being an "h1" tag

### 3. Add a photo of yourself to the page

The photo must be inserted using an **img** tag with the ID "minha_foto".

**What will be checked:**

- The photo must be inserted using an img tag with the ID "minha_foto"

### 4. Add a list of lessons learned to the page

The list must have **10** items, be numbered and have the ID "licoes_aprendidas".

**What will be checked:**

- The list must be numbered and have the ID "licoes_aprendidas"
- The list must have 10 items

### 5. Create a list of lessons you still want to learn for the page

The list must have **10** items, not be numbered and have the ID "licoes_a_aprender".

**What will be checked:**

- The list must not be numbered and must have the ID "licoes_a_aprender"
- The list must have 10 items

### 6. Add a footer to the page

The footer must use the **footer** tag and have the ID "footer".

**What will be checked:**

- The footer must have the ID "footer"

### 7. Insert at least one external link on the page

This link must be configured to open in a new browser tab

### 8. Create an article about your learning

The article must have more than 300 **characters** and less than 600, and must also have the **article** tag.

**What will be checked:**

- The `article` tag must be used
- The article must have more than 300 characters and less than 600

### 9. Create a section that tells a passage about your learning

The section must have more than 100 **characters** and less than 300, in addition it must have the **aside** tag.

**What will be checked:**

- The `aside` tag must be used
- The section must be more than 100 characters and less than 300

### 10. Apply HTML elements according to the meaning and purpose of each one

To make your website more accessible and improve its ranking in web search engines, your page must contain the following elements: article, header, nav, section, aside and footer.

**What will be checked:**

- Validate if the page has an "article" element
- Validate if the page has a "header" element
- Validate if the page has a "nav" element
- Validate if the page has a "section" element
- Validate if the page has an "aside" element
- Validate if the page has a "footer" element

### 11. Test the semantics of your page is approved by the CodeSniffer website

Test the semantics of your page is approved by the CodeSniffer website

**What will be checked:**

- Your website should pass the CodeSniffer website semantic check without any problems

### BONUS

### 12. Add a table to the page

**What will be checked:**

- The page must have a table

### 13. Use the Box model

Change **margin**, **padding** and **border** of elements to see, in practice, how these attributes influence and improve the visualization of components.

**What will be checked:**

- Change the `margin`, `padding` and `border` of the elements to see, in practice, how these attributes influence and improve the visualization of the components

### 14. Change font-related attributes
Modify the style of your typography by changing the font size, color, line spacing and **font-family**.

**What will be checked:**

- Change font size
- Change font color
- Change the spacing between lines
- Change the `font-family`

### 15. Position your article and learnings section next to each other

Add the class "left-side" to the element positioned on the left side and the class "right-side" to the element positioned on the right side

**What will be checked:**

- Use the "left-side" class
- Use the "right-side" class
- Check if elements with right-side and left-side classes are positioned correctly

---

### (OPTIONAL) After finishing development

* Go to the **YOUR** _Pull Request_ page, add the _"code-review"_ label and tag your colleagues
   * In the menu on the right, click on the _link_ **"Labels"** and choose the _label_ **code-review**
   * In the menu on the right, click on the _link_ **"Assignees"** and choose **your username**
   * In the menu on the right, click on the _link_ **"Reviewers"** and type `students`, select the team `tryber/students-sd-x`

If there are still any questions about how to deliver your project, [here is an explanatory video](https://vimeo.com/362189205).

---

## Final notices

When finalizing and submitting the project, don't forget to rate your experience by filling out the form. It takes less than 3 minutes!

Link: [PROJECT EVALUATION FORM](https://be-trybe.typeform.com/to/ZTeR4IbH)

The automatic evaluator does not necessarily evaluate your project in the order that the requirements appear in the readme. This is to make the evaluation process faster. 😉

---
