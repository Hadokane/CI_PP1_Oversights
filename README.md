![OvsLogo](assets/images/stickers/Asset%201.png)

# The Oversights - Band Website

## The digital home of the Newport based rock band.

**Developer Links:**

*(Right-click to open in new tab/window)*

[Developer - HK_Dev](https://github.com/Hadokane "Hadokane - Github")

[Commit Log](https://github.com/Hadokane/CI_PP1_Oversights/commits?author=Hadokane&since=2022-08-31&until=2022-09-20)

**Live Website Link:**

[Live Website - The Oversights](https://hadokane.github.io/CI_PP1_Oversights/ "The Oversights")

**Repository Pages:**

[Repository page - Index.html](../CI_PP1_Oversights/index.html)

[Repository page - Music.html](../CI_PP1_Oversights/music.html)

[Repository page - Shows.html](../CI_PP1_Oversights/shows.html)

[Repository page - Contact.html](../CI_PP1_Oversights/contact.html)

[Repository page - Thanks.html](../CI_PP1_Oversights/thanks.html)

## Academic Project Aims

I am currently pursuing my **Diploma in Web App Development** from [Code Institute](https://codeinstitute.net/ "code institute").

The academic aim of this project is to demonstrate my newly developed skills within the HTML & CSS languages.

I intend to display this throughout the project via my: coding, comments, commits and explination provided by this README file.

As such no other programming languages are used directly, however additional functionality is provided by the framework [Bootstrap 5.2](https://getbootstrap.com/) & a functional email form is present thanks to [Formsubmit](https://formsubmit.co/).

Great care has been taken to ensure that the website has been designed to best practices and is responsive on all screen resolutions.

It has been tested on a variety of devices, from mobiles to 4k resolution monitors and has proven compatiblity with all popular web browsers.

## Table of Contents

1. [Project Goals](#project-goals)
    - [User Goals](#user-goals)
    - [Site Owner Goals](#site-owner-goals)
2. [UX]
    -
    -

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

Kept website colours down to a minimum pallet of Black & White to reduce chances of visual noise/overwhelming visuals. Benefits being the colourful album covers and 
colourful backgrounds used on images are then able to draw the eye of the visitor ensuring they can find what they're looking for and the band are able to increase their chances
of selling merchandise or garnering listens and views. Simple colours are also a classic choices that conform to good design, allowing for a sleek, minimalistic modern look.

Possibly change all sizes to em instead of pixels down the line as it's responsive to the browser functions of zooming in the page. Good for visually impared users, set overflows to ensure text isn't cropped or lost.

Maybe Add a gallery page or gigs section?
Link externally for videos and have footer section with social links appear in bar when on small/medium devices.
Internal page for MUSIC: SHOW EP, Drop down menus for lyrics to each song. Info on each band member and mini gallery of video stills from the EP on this page if no gallery page added.
Drop down under music 1 - Hello Adventure, 2 - Coming soon (make it an inactive link.)

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

Black & White is timeless! The bands branding will evolve over time, colour pallets will change. I'd initially concidered using one.
Black & white will always work, draws users eyes to the spots of colour. BOLD Yellow on links - Makes it very clear to the user what this is.
Visually simple, modern minimalist look, has a certain edge and style to it with the bold colours making a splash. Ensures visual fidelity of images
is maintained, artwork pops, etc.

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

    The solution was to simply break it up into specific padding commands:

        .navbar_links {
            list-style: none;
            padding-top: 5px;
            padding-left: 15px;
        }
    ---

2. Youtube & Bandcamp's Embeds were unresponsive Iframes by default and needed to be styled in order to adapt to the responsive layout of the website.

    This initial code specified a width and height for the video. 

        <iframe width="560" height="315" src="https://www.youtube.com/embed/DJQ0X-z65oQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

    I'd believed that by setting the following, my issues would be solved and the design would become responsive.

            width="100%" height="auto"

    I was incorrect however and although the width now filled the container the videos height became a squashed strip that wouldn't change. The solution was to removed the width & height from the iframe and style it externally in the style.css sheet.
    
    I found guidance from this W3CSchools article. (https://www.w3schools.com/howto/howto_css_responsive_iframes.asp)

    Which taught me that to maintain the 16:9 Aspect Ratio. I needed to set the container to relative and us either top or bottom padding to keep the iframe aligned with my responsive Bootstrap code. 
    
    The 56.25 came from using the needed 16:9 ratio (9/16=0.5625).

        .yt-container {
            overflow: hidden;
            padding-bottom: 56.25%;
            position: relative;
            height: 0;
        }

        .yt-container iframe {
            left: 0;
            top: 0;
            height: 100%;
            width: 100%;
            position: absolute;
        }

    I was then able to adapt this code and alter it for use with the Bandcamp embed, allowing that to also become responsive.
   
    This time to achieve a 9:16 Aspect Ratio instead I used the default height & width values (350/621=1.7778) to determine that "177.78" would be the perfect size for padding.
    
    I adjusted this further to remove some unneccesary blank space from the widget.
    ---

3. Couldn't find a property to change the image sizes within Bootstraps card system. Led to uneven sizing across cards which looks untidy and distracting. Expected adding h-100 to the class would fix it  but this only made sure the cards themselves were the same size, not the space occupied by their contents.
        ![Before_merch](docs/screenshots/merch_before.png)
        
    Decided to simply resize the images to all have the same proportions within Photoshop and then replace the ones in use. A simple solution that achieved the results I wanted without any code changes.
        ![After_merch](docs/screenshots/merch_after.png)

---

4. one of my <-hr-> elements was larger than others. (CSS added specifically for the screenshots to make the problem more visible).
The element was making use of bootstrap code in order to appear only on small devices.


    ![bug_4](docs/screenshots/bug_hr.png)


SOLUTION: Wrap the initial code within a <-div class="col"-> in order to have it conform to Bootstraps styling.

    <div class="col">
        <hr class="d-none d-sm-block d-md-none">
    </div>
---
   ![bug_4_fix](docs/screenshots/bug_hr_fix.png)

---

5. Brand text was forcing the burger menu navbar onto the line below on smaller devices (< 450px). Bootcamp solutions
seemed to remove my icon as well leaving the bart with no branding and moving the burger menu to it's default position of floating to the left. I decided the simplist method would be to use a media query to hide just the brand text on smaller devices. Leaving the logo present in the nav bar - to maintain branding - while keeping the nav burger menu on the right hand side where users would expect it to be.

        /*--- Prevents the Brand text from pushing the navbar to the line below. Disappears before hand, leaving the logo visible*/
        @media screen and (max-width: 450px) {
            .navbar-brand{
                width: 0;
                font-size: 0;
            }
        }

## Roadmap

Further store functionality to remove third party website dependency?
Mailing List implementation?

https://getbootstrap.com/docs/5.2/components/pagination/
- Add pagination to Gallery section as more gigs are played.

---

## Credits (Programmes / Frameworks / Technologies Used)

---

1. [CI TEMPLATE](https://github.com/Code-Institute-Org/gitpod-full-template) - This repository was initially created using Code Institute's provided template.

2. [Gut42](https://gut42.com/the-oversights-hello-adventure) - For his stellar, commissioned design work on The Oversights album, logos and stickers. Used with permission throughout this website to establish a strong, branded theme.

3. [Markdown Guide](https://www.markdownguide.org/cheat-sheet/) - For use of their "Markdown Cheat Sheet" for the instructional purpose of writing this README.md file.

4. https://code-boxx.com/html-scroll-to-top-button/ - Back to top of page, simple code with no Javascript.

5. https://usbrandcolors.com/youtube-colors/ - Giving me the correct logo hex colors to use on the background of buttons.

6. https://fontawesome.com/ - Icons

7. https://compressjpeg.com/ - Compressing images to keep image size down.

8. https://png2jpg.com/ - png to jpg conversion

9. https://formsubmit.co/ - for functioning email form

10. https://www.youtube.com/watch?v=Yg6POD0M30w&ab_channel=ADesignerWhoCodes - for tutorials on functioning email forms.

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