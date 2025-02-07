### HTML Basics

## Introduction

This is a basic portfolio website [project from roadmap frontend's learning](https://roadmap.sh/projects/basic-html-website) that highlights my knowledge in using HTML. Moreover, I styled the same using [this guideline](https://roadmap.sh/projects/portfolio-website) It will have four pages;

1. **Home Page**
2. **Projects Page**
3. **Articles Page**
4. **Contact Page**

The details about the start date will be highlighted as a comment in the index.html page which is also the homepage.

I will also try to write comments in the pages as much as I can. The descriptions of what I have done will follow below.

## Home Page

The homepage of this project houses the navigation bar that has the links to the other pages of the portfolio website.

Besides the *navigation bar*, the homepage has an *about* section and a section that gives a brief of my achievements.

In each of these sections I used the ``` <section> ``` tag to divide the areas into sections. It will also provide good ground for when I will style the website.

# Other Pages
## Projects Page

The projects page has the links to the different projects I have been doing. These projects are in ``` <div> ```s again so that it becomes easier to style the pages later.

## Articles Page

In the articles page I did short descriptions of the projects I did. I provided links to README documents for the different projects in the <ins>*Projects*</ins> page.

## Contact Page

The contact page basically has a form in which the user can ssend feeback, including inserting their *email*, *phone number* and *name*.

Here is a snippet of the form. It is my first HTML form to make.
``` 
<form method="post">
        <p>
            <label for="fname">First Name:</label>
            <input type="text" id="fname" required/>
        </p>
        <p>    
            <label for="lname">Last Name:</label>
            <input type="text" id="lname" required/>
        </p>
        <p>
            <label for="mail">Email:</label>
            <input type="email" id="mail" required />
        </p>
        <p>
            <label for="message">Give me feedback:</label>
            <textarea type="textarea" id="message" required></textarea>
        </p>    
    </form> 
```

_**PS:**_ I discovered a way to add the copyright logo to the footer of each of the pages using ``` &copy; ```. Also, each page has the navigation links besides the *home page*.