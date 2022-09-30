# DXB111 » Introduction to web design
<details><summary><h2>Assessment 1 » Initial web prototype</h2></summary>

### Description
You will produce an initial web-based prototype developed using HTML and CSS. This should demonstrate your skills in translating a concept into an effective web-based prototype.

### Weight
40%

### Due date
11:59pm on Friday, 16th September 2022

### Format
ZIP file archive of completed website uploaded through the Assessment 1 submission form on Blackboard.

<br />

## To Do
- [x] Footer
- [x] References (hide/show?)
- [x] Description [`index.html`]
- [x] Description [`contact.html`]
- [x] Maybe add some more icons to the socials
- [x] pfp img
- [x] works imgs and info and remove temp imgs
- [x] clean up css, add some titles?
- [x] nav bar what page ur on
- [x] test turn off js
- [x] go through css, optimise, make better, get good
- [x] css, remove anything that repeats itself
- [x] change the icons
- [x] w3 validator
- [x] CC/copyright? (`https://creativecommons.org/choose/`)

<br />

## Checklist
### Basics
- [x] I have three HTML files named `index.html`, `works.html`, `contact.html`.
- [x] My images have sensible names and are likely stored in a folder called `images`.
- [x] My images are optimised (likely as JPG or PNG images).
- [x] I have a CSS file with a sensible name.
- [x] I have validated each of my HTML and CSS files.

<br />

### For each of my HTML files
#### Frontmatter
- [x] My doctype is specified as HTML as the first line: `<!DOCTYPE html>`.
- [x] I have opening and closing `<html>`, `<head>`, `<body>` tags.
- [x] My language is specified as English: `<html lang="en">`.
- [x] I have `<meta>` tags for: `charset`, `author`, `description`, and `viewport` for each page, where the description is unique to each page.
- [x] I have a `<title>` specified inside the `<head>` that is unique to each page.
- [x] I have a `<link>` tag which is inside the `<head>` for linking my CSS which contains all of the CSS for my whole site
- [x] I have no inline or internal CSS.

#### Inside the `<body>` of each page
- [x] I have a navigation bar using the `<nav>` tag (possibly but not necessarily inside a `<header>` tag).
  - [x] This code can be copied and pasted to all three pages, and then changed to make it clear which page is currently active.
- [x] I have a footer using the `<footer>` tag.
  - [x] This code will typically be the same on all three pages of your site.
- [x] I have one and only one top level heading in my page using `<h1>`.
  - [x] I am aware that the different heading levels `<h1>`, `<h2>`, `<h3>`, etc. are the only tags that use numbers.
  - [x] I’m aware that there can be many `<h2>` headings and that this indicates that they are “second level”.

#### Inside my CSS
- [x] I have one single CSS file that is used across all three of my pages.
- [x] If I’ve used web fonts (like those from google) I have those imported at the top of my CSS file.
- [x] I have sincerely tried to avoid repeating myself too much (and am aware that I can discuss ways to do this with my tutor in week 7).
- [x] I have used classes (and possibly IDs where appropriate) to avoid repeating myself too much.

#### Extra things
- [x] I have read the rubric and the brief and I’m aware that there are more things to do that aren’t on this list.
- [x] I’ve tested my site on someone else’s computer (e.g. emailing it as a ZIP file or using a USB drive then opening it elsewhere) to make sure that I haven’t used absolute links to files or images and haven’t used local fonts, etc.
- [x] I haven’t used JS, Bootstrap (or any framework) and the code is all my own.
- [x] If I’ve used code snippets from examples I’ve used comments in HTML and CSS to show that I understand what is going.
</details>

<details><summary><h2>Assessment 2 » High-fidelity web prototype</h2></summary>

### Description
You will produce an initial web-based prototype developed using HTML and CSS. This should demonstrate your skills in translating a concept into an effective web-based prototype.

### Weight
60%

### Due date
11:59pm on Friday, 11th November 2022

### Format
Submit via Blackboard in the “Assessment” section. Submit a single zip file containing all content. Give this file a name that includes your name, your student ID, AS2, and your tutor’s name. Example: `DeliaSingh_12345678_DXB111_AS2_nick.zip`

<br />

## Checklist
- [ ] My HTML files have sensible names and are organised in some way.
- [ ] I have eight HTML files: a home page, two category pages, four destination pages, and an about page.
- [ ] I have produced a rationale document that makes it clear who I’m designing this site for.
- [ ] My images have sensible names and are likely stored in a folder called “images” and have no special characters or spaces in the file names.
- [ ] My images are optimised (likely as JPG or PNG images, normally <1MB each).
- [ ] I have one CSS file with a sensible name (possibly more than one if needed, but certainly not one per page).
- [ ] I have validated my HTML and CSS files using the W3C validators.
- [ ] I have tested my website in the Chrome browser and checked how it works at different sizes.
- [ ] I have made my code easy to read with nice indentation (you can use a plugin for this) and comments.

### Frontmatter
For all of my HTML files I have done the following:
- [ ] My doctype is specified as HTML as the first line: `<!DOCTYPE html>`.
- [ ] I have opening and closing `<html>`, `<head>`, `<body>` tags.
- [ ] My language is specified as English: `<html lang="en">`.
- [ ] I have `<meta>` tags for: charset, author, description, and viewport for each page, where the description is unique to each page.
- [ ] I have a `<title>` specified inside the `<head>` that is unique to each page.
- [ ] I have a `<link>` tag which is inside the `<head>` for linking my CSS which contains all of the CSS for my whole site (I have no inline or internal CSS).


Example of all of this being done well:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Title here</title>
    <meta charset="utf-8" />
    <meta name="author" content="Nick Kelly" />
    <meta name="description" content="Description here" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="filename.css" />
  </head>
  <body>
  <!--rest of site here-->
```

### Inside the `<body>` of each page
- [ ] I have a navigation bar using the `<nav>` tag (possibly but not necessarily inside a `<header>` tag).
  - [ ] This code might be copied and pasted to all pages, and then changed to make it clear which page is currently active.
- [ ] I have a footer using the `<footer>` tag
  - [ ] This code will typically be the same on all pages of your site
- [ ] I have one and only one top level heading in my page using `<h1>` 
  - [ ] I am aware that the different heading levels `<h1>`, `<h2>`, `<h3>`, etc. are the only tags that use numbers.
  - [ ] I’m aware that there can be many `<h2>` headings and that this indicates that they are “second level”.

### Inside the CSS
- [ ] If I’ve used web fonts (like those from google) I have those imported at the top of my CSS file.
- [ ] I have sincerely tried to avoid repeating myself too much.
- [ ] I have used groups, classes, the hierarchy (and possibly IDs where appropriate) to avoid repeating myself too much.

### Important things
- [ ] I have read the rubric and the brief and I’m aware that there are more things to do that aren’t on this list.
- [ ] I have read and considered each of the items in the Guide to Accessibility for AS2 file that’s in this same folder.

### Rationale
- [ ] I have included an A4 PDF with my rationale.
- [ ] It includes a 200 word statement of my target audience (i.e., what kind of 10-year olds?).
- [ ] A one-page mood board of inspiration (no attribution needed for this).
- [ ] It includes three lo-fi wireframes for one of my pages (e.g., your destination page design in each of mobile, tablet, and desktop sizing.
- [ ] It includes three screenshots with annotations (consider approx. 10-20 annotations) showing how my design has met the needs of the brief.

### Extra things
- [ ] I’ve tested my site on someone else’s computer (e.g., emailing it as a ZIP file or using a USB drive then opening it elsewhere) to make sure that I haven’t used absolute links to files or images and haven’t used local fonts, etc.
- [ ] I haven’t used JS, Bootstrap (or any framework) and the code is all my own.
- [ ] If I’ve used code snippets from examples, I’ve used comments in HTML and CSS to show that I understand what is going 
- [ ] I have considered basic usability principles in my design and have used reasonable font sizing throughout and enough contrast between text and background elements.

## Design Brief
Design and implement a responsive website that serves as a travel guide for anybody to become interested in some aspect of your local suburb/town/part of the city (e.g. “come and visit” or highlighting particular places [e.g. playgrounds, shops, parks, gardens, etc.]). It should meet criteria of:

### Design Criteria
1. Meet the expectations of a particular target audience. It must be designed to work for the age range of people who are approximately 10 years old.
2. Have eight web pages:
  - [ ] One home page (index.html).
  - [ ] Two category pages (e.g., ways to group location pages. Examples: “natural beauty”, “places to shop”, “local characters”, “historical sites”, etc.).
  - [ ] Four (minimum) different location (or destination/feature/landmark/place) pages. These should each be categorised within at least one of your two categories. (They are indicative of what the site would look like with, say, 20 locations; but we’re not asking you to make those so that you can focus on your design skills)/
  - [ ] One about page that includes your details, references, and info about the website.
3. Include a header, nav bar, and footer that are consistent across all of your pages
  - Think about usability and information architecture in considering how users navigate your site
4. Be designed responsively to work for all three of mobile, tablet, and desktop.
  - The assignment will be viewed in three sizes during marking:
    - [ ] Mobile phone (iPhone X, which is 375px wide).
    - [ ] Tablet (iPad, which is 768px wide).
    - [ ] Desktop (1440px wide).
5. Be a WCAG Level A accessible website:
    - For this purpose, defined as meeting WCAG 2.1 Level A standard (noting that most government agencies require AA standard).
    - https://www.w3.org/WAI/WCAG21/quickref/ (items labelled Level A).
    - Refer to notes in AS2 reference in the OneDrive folder for how to achieve this (Week 11).
6. Have aesthetic quality (e.g., choice of media, colours, typography, sizing, layout, etc.).
7. Has a coherent graphical identity.
8. Have content that matches the user group.
    - We recommend creating your own media (i.e., photos) for this assignment.
    - You should do this a COVID-safe way following the QLD health advice of the day.
9. Obey copyright laws and cite any work that you use
    - This applies to images and text

### Code Criteria
10. Make use of HTML tags in a semantic way.
11. Ensure full separation of page content and styling using CSS.
12. Use appropriate layout and styling of code in both HTML and CSS (i.e., indents, grouping, comments where appropriate).
13. Appropriately use responsive design (through use of appropriate CSS, such as flex and/or breakpoints, etc.) to achieve the website design.

### Rationale Criteria
14. Rationale should be a PDF document in A4 size with as many pages as is needed (landscape orientation preferred but not mandated).
15. An approx. 200-word statement describing your interpretation of the target audience (who must be under 10 years of age).
16. A one-page mood-board showing snapshots of inspiration/artworks/resources/colours/extracts of sites that you are taking your inspiration from.
17. Include three low-fidelity wireframes for one of your pages (e.g., a category page) that show this page in each of the three different sized viewports.
18. Exactly three screenshots from your site with as many annotations as you like (totalling less than 800 words) noting some design decisions that you made and your rationale for those decisions (as in, why you chose this). For example, you might have 12 annotations of ~60 words each.
    - Make connections between your decisions and the target audience
    - Make reference to your consideration of accessibility in your design
</details>
