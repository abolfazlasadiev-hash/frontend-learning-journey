# About Me Page

## Project Overview

This project is the **second project** in my frontend development learning journey.

The goal of this project is to create a more detailed personal webpage using **HTML only**. Unlike the Personal Profile Page, this project focuses more on organizing longer personal information into meaningful sections.

The page introduces who I am, my learning journey, my goals, hobbies, interests, and the technologies I am currently learning.

This project is part of **Category 01 — HTML Fundamentals**.

---

## Project Goals

The main goals of this project are:

* Practice writing HTML from scratch
* Improve understanding of HTML document structure
* Learn how to organize longer content
* Practice using semantic HTML elements
* Use headings correctly
* Practice ordered and unordered lists
* Add and display an image
* Create links to external websites
* Improve accessibility with meaningful `alt` text
* Build a complete webpage without CSS or JavaScript

---

## Technologies Used

This project was built using:

* HTML5
* Git
* GitHub
* Visual Studio Code
* Browser Developer Tools

No CSS or JavaScript is used in this project.

---

## Page Sections

The About Me Page contains several sections.

### 1. Header

The header introduces the website and provides the main title.

Example content:

* My name
* Frontend development learner
* Navigation links

---

### 2. Who I Am

This section provides a short introduction about me.

It explains:

* Who I am
* What I am interested in
* Why I am learning frontend development

---

### 3. My Story

This section contains a longer description of my learning journey.

The purpose is to practice organizing paragraphs and presenting information in a readable structure.

---

### 4. What I'm Learning

This section describes the technologies and concepts I am currently studying.

For example:

* HTML
* CSS
* JavaScript
* Git
* GitHub
* Web development fundamentals

---

### 5. My Goals

This section describes my short-term and long-term goals.

An ordered list can be used when the goals have a specific order or priority.

Example:

1. Improve my HTML skills
2. Learn CSS
3. Learn JavaScript
4. Build more projects
5. Create real-world web applications

---

### 6. My Hobbies and Interests

This section contains a list of activities and subjects that I enjoy.

An unordered list is appropriate because the items do not have a specific order.

---

### 7. What I'm Working On

This section describes the projects and exercises I am currently working on as part of my frontend learning journey.

---

### 8. Technologies I Like

This section lists technologies that I am interested in learning or using.

---

### 9. Find Me Online

This section contains links to online profiles such as GitHub.

The GitHub link should point to my actual GitHub profile.

---

### 10. Footer

The footer contains basic information about the website and copyright information.

---

# HTML Concepts Practiced

This project focuses on several important HTML concepts.

## HTML Document Structure

The page uses the standard HTML5 structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
</head>

<body>

</body>
</html>
```

---

## Headings

Headings are used to organize the page into sections.

Examples:

```html
<h1>About Me</h1>

<h2>Who I Am</h2>
<h2>My Story</h2>
<h2>My Goals</h2>
```

The `<h1>` represents the main page heading, while `<h2>` elements represent major sections.

---

## Paragraphs

Paragraphs are used for longer written content.

```html
<p>
    I am currently learning frontend development and building
    projects to improve my skills.
</p>
```

---

## Strong Text

The `<strong>` element can be used when specific text has strong importance.

Example:

```html
<p>
    My main goal is to become a <strong>frontend developer</strong>.
</p>
```

---

## Unordered Lists

Unordered lists are useful for hobbies, technologies, and other items where order is not important.

```html
<ul>
    <li>Programming</li>
    <li>Reading</li>
    <li>Learning new technologies</li>
</ul>
```

---

## Ordered Lists

Ordered lists are useful when the order of items matters.

```html
<ol>
    <li>Learn HTML</li>
    <li>Learn CSS</li>
    <li>Learn JavaScript</li>
</ol>
```

---

## Images

The project includes a profile image.

Example:

```html
<img
    src="profile.jpg"
    alt="Profile picture"
    width="200"
>
```

The `alt` attribute provides alternative text for users who cannot see the image.

---

## Links

The page includes links to external websites.

Example:

```html
<a
    href="https://github.com/abolfazlasadiev-hash"
    target="_blank"
    rel="noopener noreferrer"
>
    GitHub
</a>
```

---

# Semantic HTML

This project also introduces semantic HTML elements.

Examples include:

```html
<header>
</header>

<main>
</main>

<section>
</section>

<footer>
</footer>
```

These elements help describe the meaning and structure of the content.

For example:

* `<header>` contains introductory content
* `<main>` contains the primary page content
* `<section>` groups related content
* `<footer>` contains footer information

---

# Project Structure

The project has the following structure:

```text
category-01-html-fundamentals/
└── 02-AboutMePage/
    ├── index.html
    ├── profile.jpg
    └── README.md
```

### `index.html`

Contains the complete About Me webpage.

### `profile.jpg`

The profile image displayed on the webpage.

### `README.md`

Contains the documentation for the project.

---

# How to Run the Project

No installation or build process is required.

### Step 1

Open the project folder:

```text
02-AboutMePage
```

### Step 2

Open:

```text
index.html
```

in a web browser.

### Step 3

Review the page and test the links and image.

You can also use the **Live Server** extension in Visual Studio Code if you have it installed.

---

# Testing

The page should be tested in a browser before considering the project complete.

## Basic Testing Checklist

* [ ] Page opens correctly
* [ ] Page title appears in the browser tab
* [ ] Main heading is visible
* [ ] All sections are visible
* [ ] Paragraphs display correctly
* [ ] Profile image loads correctly
* [ ] Image has meaningful `alt` text
* [ ] Unordered lists display correctly
* [ ] Ordered lists display correctly
* [ ] GitHub link works
* [ ] External link opens correctly
* [ ] No broken links
* [ ] No missing images
* [ ] No HTML errors

---

# Testing With Browser Developer Tools

I can use browser Developer Tools to inspect and test the webpage.

### Elements / Inspector

Use the Elements panel to inspect:

* Headings
* Paragraphs
* Images
* Links
* Lists
* Sections

This helps verify that the HTML structure is correct.

### Console

Open the Console and check whether the browser reports any errors.

### Device Toolbar

The Device Toolbar can be used to preview the webpage at different screen sizes.

Even though this project does not use CSS yet, checking different viewport sizes helps me understand how HTML content behaves.

---

# Accessibility

Accessibility is an important part of building websites.

This project practices some basic accessibility principles.

### Image Alt Text

The profile image should have descriptive alternative text:

```html
<img src="profile.jpg" alt="Profile picture">
```

### Heading Hierarchy

Headings should follow a logical structure.

For example:

```text
H1
 ├── H2
 ├── H2
 ├── H2
 └── H2
```

### Meaningful Links

Links should clearly describe their destination.

For example:

```html
<a href="https://github.com/abolfazlasadiev-hash">
    GitHub
</a>
```

---

# What I Learned

By completing this project, I practiced:

* Creating a complete HTML document
* Structuring a webpage
* Using headings and paragraphs
* Organizing content into sections
* Using ordered lists
* Using unordered lists
* Adding images
* Writing useful `alt` text
* Creating external links
* Using semantic HTML
* Understanding basic accessibility
* Testing HTML in a browser
* Using Developer Tools
* Organizing a project directory
* Tracking project files with Git

---

# Difference From Project 1

The first project was a simple **Personal Profile Page**.

This project goes one step further by requiring more detailed content and better organization.

### Project 1

Focused on:

* Basic HTML structure
* Personal introduction
* Profile image
* Skills
* Hobbies
* GitHub link

### Project 2

Adds:

* A longer biography
* Personal story
* Learning journey
* Goals
* More detailed sections
* Ordered lists
* Strong text
* More content organization
* Greater focus on semantic structure

The main lesson is that HTML is not only about displaying text. It is also about giving content a meaningful structure.

---

# Limitations

This project intentionally uses only HTML.

It does not currently include:

* CSS styling
* Responsive design
* JavaScript
* Animations
* Interactive components
* Form validation
* Backend functionality

These features will be introduced in later projects.

---

# Future Improvements

After learning CSS and JavaScript, this project could be improved by adding:

* A professional visual design
* Responsive layouts
* Navigation styling
* Better typography
* Colors and spacing
* Interactive elements
* A dark/light theme
* Animated sections
* Contact form functionality

However, these improvements are intentionally postponed because this project focuses on **HTML fundamentals**.

---

# Roadmap Position

This is:

**Project 2 / 100**

### Category

**01 — HTML Fundamentals**

### Project

**02 — About Me Page**

### Previous Project

**01 — Personal Profile Page**

### Next Project

**03 — Resume Page**

---

# Learning Objective

The main objective of this project is to become more comfortable creating structured webpages with HTML before introducing CSS and JavaScript.

The goal is not just to copy an example, but to understand why each HTML element is being used.

A good test of understanding is:

> Can I create this page again from an empty `index.html` without looking at the original code?

If the answer is yes, the concepts are becoming familiar.

---

# Git

After completing and testing the project, the files can be committed to Git.

Check the project status:

```bash
git status
```

Add the project:

```bash
git add category-01-html-fundamentals/02-AboutMePage/
```

Commit the project:

```bash
git commit -m "Add about me page"
```

Push it to GitHub:

```bash
git push origin main
```

Then verify:

```bash
git status
```

The goal is to see:

```text
nothing to commit, working tree clean
```

---

# Project Information

| Item            | Information       |
| --------------- | ----------------- |
| Project         | About Me Page     |
| Project Number  | 02                |
| Category        | HTML Fundamentals |
| Main Technology | HTML5             |
| CSS             | Not used          |
| JavaScript      | Not used          |
| Git             | Yes               |
| GitHub          | Yes               |
| Status          | In Progress       |

---

# Author

**Abolfazl Asadi**

Frontend Development Learner

GitHub: `abolfazlasadiev-hash`

---

# Status

**In Progress**

The project can be marked as **Completed** after:

* The HTML page is finished
* The profile image works
* All links work
* The page has been tested
* Developer Tools have been checked
* The README is complete
* The project has been committed to Git
* The project has been pushed to GitHub
