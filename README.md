![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

This is the README.md file for my Code Institute project.

I'm currently laying out a "project skeleton" for Initial Commit purposes and will be updating
this more and more as I progress through the project.

## Python Reminder

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

**List Example**

- Item 1
- Item 2
- Item 3

**Example**

Examples of code in a box.

```
pkill uptime.sh
rm .vscode/uptime.sh
```
    or just press tab to indent.

---

# The Oversights

## Introduction

---
**A website for the Newport-based Alt. Rock Band.**

***Personal aims & overview of site***

## Table of Contents

---

## UX

---

### User Experiences & Goals

------

**Target Audience**

Info goes here.

**First-time User**

Info goes here.

**Returning User**

Info goes here.

**Band / Site owners**

Info goes here.

---

### Design choices

---

**Features**

Info goes here. Mention burger menu on right-hand side being beneficial as most users are right-handed and can then navigate the site comfortably with one hand.

**Wireframes**

Initial wireframe design for the websites home page layout. Includes both mobile & computer.

Shows collapsable nav bar conforming to responsive design best practices.

Features include:
- displaying an external link to the EP or an embedded player from spotify.
- embedding the latest Youtube music video.
- Promoting merchandise to drive sales.
- Including social links in two different accessible places. Changing based on the responsive layout so that they're always convenient for the user to find.

![Index Wireframe](docs/wireframes/wireframe_index.png)


Info goes here.

**Font / Typography**

Info goes here.

**Colour Pallet**

Info goes here.

**Images & Logo Choices**

Info goes here.

## Features of the website

---

## Testing

**Validation Tests**

Info goes here.

**Screen Reader**

Info goes here.

**Different browsers & devices**

Info goes here.

**User stories met?**

Info goes here.

---

## Bugs

Let's hope very few!

1. Using the condensed Padding CSS was not effecting the navbar at all.
    .navbar_links {
        list-style: none;
        padding: 15px, 0px, 0px, 15px;
    }

    Solution was to break it up:
    .navbar_links {
        list-style: none;
        padding-top: 5px;
        padding-left: 15px;
    }
---

## Future Enhancements

Further store functionality to remove third party website dependency?
Mailing List implementation?

---

## Credits (Programmes / Frameworks / Technologies Used)

---

1. [CI TEMPLATE](https://github.com/Code-Institute-Org/gitpod-full-template) - This repository was initially created using Code Institute's provided template.
2. [Gut42](https://gut42.com/the-oversights-hello-adventure) - For his stellar, commissioned design work on The Oversights album, logos and stickers. Used with permission throughout this website to establish a strong, branded theme.

1. [Markdown Guide](https://www.markdownguide.org/cheat-sheet/) - For use of their "Markdown Cheat Sheet" for the instructional purpose of writing this README.md file.

---

## Deployment

---

---

## Acknowledgements

---

With thanks to:
- My fellow "Oversights" for trusting me with this task and providing helpful feedback throughout.
- My family and friends - for keeping me on task and providing a helpful eye or a pair of testing hands when needed.
- Code Institute & it's community at large, for providing me with the necessary skills, knowledge and guidance to pull this project off.

[Back to top ↑](#the-oversights)

---