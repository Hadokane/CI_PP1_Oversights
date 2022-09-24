![OvsLogo](assets/images/stickers/Asset%201.png)

# The Oversights - Band Website

## The digital home of the Newport-based rock band.

![UI](docs/ui/ui_responsive.png)

**Developer Links:**

*(Right-click to open in a new tab/window)*

[Developer - HK_Dev](https://github.com/Hadokane "Hadokane - Github")

[Commit Log](https://github.com/Hadokane/CI_PP1_Oversights/commits?author=Hadokane)

**Live Website Link:**

[Live Website - The Oversights](https://hadokane.github.io/CI_PP1_Oversights/ "The Oversights")

**Repository Pages:**

[Repository page - Index.html](../CI_PP1_Oversights/index.html)

[Repository page - Music.html](../CI_PP1_Oversights/music.html)

[Repository page - Shows.html](../CI_PP1_Oversights/shows.html)

[Repository page - Contact.html](../CI_PP1_Oversights/contact.html)

[Repository page - Thanks.html](../CI_PP1_Oversights/thanks.html)

---
## Academic Project Aims
---

I am currently pursuing my **Diploma in Web App Development** from [Code Institute](https://codeinstitute.net/ "code institute").

The academic aim of this project is to demonstrate my newly developed skills within the HTML & CSS languages, through the creation of a static, front-end website.

I intend to display this throughout the project via my: coding, comments, commits and explanation provided by this README file.

As such, no other programming languages are directly used. 

However, additional functionality has been provided by the framework [Bootstrap 5.2](https://getbootstrap.com/) and a functional email form is present thanks to [Formsubmit](https://formsubmit.co/).

Great care has been taken, to ensure that the website is designed to meet best practice standards, and is responsive on all screen resolutions.

It has been tested on a variety of devices and screen resolutions, from mobiles to 4k-monitors, and has proven compatibility with all popular web browsers.

---
## Table of Contents
---

1. [User Experience (UX)](#user-experience---ux)
    - [Strategy Plane](#strategy-plane)
        - [User Stories](#user-stories)
    - [Scope Plane](#scope-plane)
    - [Structure Plane](#structure-plane)
        - [Interaction Design (IXD)](#interaction-design---ixd)
    - [Skeleton Plane](#skeleton-plane)
        - [Wireframes](#wireframes)
    - [Surface Plane](#surface-plane)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
    - [Languages](#languages)
    - [Frameworks & Tools](#frameworks-&-tools)
4. [Validation](#validation)
    - [HTML Validation](#HTML-validation)
    - [CSS Validation](#CSS-validation)
5. [Testing](#testing)
    - [Accessibility](#accessibility)
    - [Performance](#performance)
    - [Device testing](#performing-tests-on-various-devices)
    - [Browser compatibility](#browser-compatability)
6. [Bugs](#Bugs)
7. [Deployment](#deployment)
8. [Credits](#credits)
    - [Acknowledgements](#acknowledgements)

---
## User Experience - UX
---

I have decided to arrange my UX analysis by referencing Jesse James Garrett's philosophy of the "5 Planes" framework as discussed in his book [The Elements of User Experience](https://www.amazon.co.uk/Elements-User-Experience-User-Centered-Design/dp/0321683684/ref=asc_df_0321683684/?tag=googshopuk-21&linkCode=df0&hvadid=311000051962&hvpos=&hvnetw=g&hvrand=10376246921916888236&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1007448&hvtargid=pla-432330338546&psc=1&th=1&psc=1).

Through this methodology, I will establish the goals of my project, in meeting the needs of both the user and site owner.

I will maintain a clear, justified development path, and establish a defined priority of tasks and elements for integration. Ensuring the project avoids "feature creep," maintains its initial scope and meets the defined user needs.

---
### Strategy Plane
---

**Project Goals**

The aims of this project are: to design a webpage that meets the needs of an established Rock band and their fans, both long-term and new.

**Band Goals:**

The band were interviewed, and together we decided upon the following core goals:

- Promotion of their music and videos (content) is a priority.
- Promotion of their merchandise.
- Increase their social media following.
- Catalogue their releases & shows they've played.
- Improve booking opportunities by providing a method of contact for event managers.

**User Goals:**

Close friends and fans were then interviewed on what features would be important to them:

- Easy access to the band's content.
- Finding desired information with ease.
- Not having to navigate through a cluttered layout.
- Seeing photos from their shows.

**Event Managers:**

An additional group of users that can't be overlooked, are *event managers.*

Their goals would align heavily with the band's goal of "Improving booking opportunities," as they would be offering said opportunities. 
Both parties would be looking for a simple way to communicate and capitalise on each other. 

Therefore their goals would be to:

- Gather more information on the band.
- Contact them with booking information for a show/gig/event.

**User Expectations:**

After carrying out the above research, I have assembled the following "grid of opportunities" to showcase what features to prioritise heading into the next stage of development.

*GRID OF OPPORTUNITIES:*

| Opportunity | IMPORTANCE  | VIABILITY   |
| ----------- | ----------- | ----------- |
| Promote Content | 5 | 5 |
| Promote Merchandise | 4 | 3 |
| Gain Social Media Followers | 4  | 5 |
| Provide Musical Information | 2 | 4 |
| Provide a functioning contact form | 4 | 2 |

[Back to top ↑](#the-oversights---band-website)

### User Stories
---

The following user stories have been numbered sequentially so that they may be referenced in later sections.

For example: 

    (Goal's achieved: 2, 6, 9)

Would show that:

    First-time User Goals: #2; #6;
    and Returning User Goals: #9;
    have been met by the described element.

**First-time Users:**

1. As a first-time user, I want to be able to find the band's music.
2. As a first-time user, I want to be able to find the band's videos.
3. As a first-time user, I want to read about the band's history.
4. As a first-time user, I want to be able to see a list of shows the band have played.
5. As a first-time user, I want to be able to simply navigate the website.
6. As a first-time user, I want to be able to find links to their social media pages.

**Returning Users**

7. As a returning user, I want to see new content first.
8. As a returning user, I want to find information on new releases.
9. As a returning user, I want to purchase merchandise.
10. As a returning user, I want to see if they're playing a show near me.

**Event Managers**

11. As an event manager, I want to be able to contact the band and receive confirmation the message has been sent.
12. As an event manager, I want to be able to review the band's music to confirm they're a good fit for my event.

**Site Owner**

13. As a site owner, I want to be able to show my content to fans.
14. As a site owner, I want users to have a smooth experience.
15. As a site owner, I want users to see what I have for sale.
16. As a site owner, I want event managers to be able to contact me.
17. As a site owner, I want to increase my social media following.
18. As a site owner, I want to catalogue my live show gallery.

**Competitor Analysis**

With the user stories in mind, I decided it would be prudent to examine what existing websites within the Rock music community offered their fans.

This would be invaluable research as it would allow me to confirm:
- What works visually? (Design, colours, typography, etc.)
- What provided a good user experience? (Navigation methods, buttons, interactivity, etc.)
- How did they meet relevant user needs? 
- What had they done to set/achieve culturally appropriate content? (In this case, the culture of Rock Music as shown in imagery, design, layout etc.)

I examined the following pages:

[The Rolling Stones](https://rollingstones.com/)

[The Beatles](https://www.thebeatles.com/)

[FIDLAR](https://fidlar.komi.io/)

[RHCP](https://redhotchilipeppers.com/)

[Soundgarden](https://www.soundgardenworld.com/)

Seeing their responsive designs between mobile and desktop along with their strong emphasis on a balance between branding and clarity.

This has strengthened my faith in the above user stories and will help shape my thought process as I move through each design plane. 

[Back to top ↑](#the-oversights---band-website)

---
### Scope Plane 
---

It is within this plane that I will address, the features required to meet the established by the "User Stories" section of the Strategy Plane. These goals will allow me to avoid "feature creep" and maintain an agile approach to the development of the website.

**To meet the band's needs:**

- We will showcase their content (Music & Video) front and centre.
    - External iframes will allow us to embed the content directly from their social platforms. This further advertises their channels to users and may lead to conversions and increase their following.
- Merchandise will be featured on the Index page as the second highest priority.
    - Providing an external link to their store in the nav bar, will ensure it's visible from every page of the website.
- Social media icons will be present and frequent throughout the website, without subtracting from the user's experience by cluttering pages.
    - Keep the direct icons in the footer of each page. Allows the user freedom in when they choose to interact with them.
- Provide a "Shows" page to catalogue the band's events and photographs within a gallery section.
- Provide a "Music" page to catalogue the band's releases.
- The design will be kept minimalistic in terms of colour.

**To meet the user's needs:**

The above features already address several needs, such as the content being front and centre and links to the band's external social platforms being readily available on all pages.

To further improve the user's experience we can:
- Move the icons from the footer to the collapsed "hamburger menu" navbar on smaller devices.   
    - This improves the visibility of the icons and the frequency of the user interacting with them. Subtly promoting them without impacting the user's experience.
    - Furthermore, it improves the overall responsive nature of the website across different resolutions and devices.
- Provide a gallery section on the "Shows" page to allow users to view images from the band's recent events.
- The design will be kept minimalistic in terms of colour. Allowing for a smooth user experience. 
    - Avoid cluttered designs, and harsh differences in contrast, while allowing imagery to pop. Ensuring the user has an easier time finding what they need.
- New releases will be highlighted by interesting flavour text and put at the top of pages so returning users will see this first.
- Provide information on the "Music" page. 
    - Summarise the band's history.
    - Describe the releases.
- A contact form will be provided for Event Managers to reach out to the band. Requires only essential information. 

**Features Required:**

The above analysis has led me to plan the following features for implementation on the website. The specific types of content required for each are also mentioned.

The following are written in order of priority and will have dedicated sprints (of ~day) for each element:

- Responsive Navigation Bar
    - The highest priority. Featured on all pages.
    - To comply with best practices and a mobile-first approach to development, the navigation menu will display in full on medium or larger screens, and as a collapsed "hamburger menu" icon on smaller devices.
    - The social media icons will only appear on the collapsed version of the menu to improve their visibility and the user's experience by removing the effort of having them scroll to the bottom of a longer (bootstrap columns filling more of a smaller screen) page to access them.
 - Responsive Footer
    - Featured on all pages. 
    - Responsive nature is important for the user experience. Smaller screen sizes with move social media icons, therefore they are hidden at this size and moved to the nav bar, only being displayed here on larger screens.
    - Include a button to take you back to the top of each page. Saves the user from having to scroll back up, thus improving their overall experience.
- Index Page
    - The home page. The main hub of the website. The place the user will begin their journey.
    - Required: responsive iframes from websites such as Bandcamp, Spotify & Youtube.
    - Bootstrap cards are used to show individual merchandise items in a row.
    - Feature: music; videos; and merchandise; in that priority order.
- Shows Page
    - It was decided it's more beneficial for this to serve as a catalogue of past shows rather than an advertisement for future ones.
    - Gallery section to document past shows.
    - Show a featured image for each. Clicking the image will open a fullscreen gallery. This way the design remains clutter-free and the user can see at a glance, what they're looking for.
- Music Page
    - Article-style layout. Image left-aligned in an aside. Information is present on the right. Give an easy-to-read, minimalistic appearance.
- Contact Form
    - For Event Managers specifically. The least priority as they can - and most likely will - get in touch with the band via social platforms like Facebook and likely make up the smallest pool of users.
    - Use required tags to ensure messages are sent with all relevant information.
    - "Show don't tell" by using contextual icons and example placeholder text such as "John Doe" in inputs. Improves the overall user experience. 
- Bootstrap Alerts 
    - Can be used to provide additional information to users without disrupting the flow of pages.
    - Pre-empt confusion on pages like "shows" with a message redirecting Event Managers to the "contact form" instead.
    - Can be included in the gallery section also to mention that users should head over to Facebook to see recent show announcements. Making them aware that this information isn't present and providing a solution to their problem without them having to search.  

**Road Map:**

These ideas have been postponed for future updates and refinement.

- Shows Page
    - A list of upcoming shows is added at the top. Currently, the band are recording music and has nothing upcoming. As such this section won't be included in this initial sprint. An alert can be included to redirect attention toward their Facebook page. Shows can be announced on short notice, so the viewers benefit more from finding this information on an external social platform.
    - Add [Pagination](https://getbootstrap.com/docs/5.2/components/pagination/) to the Gallery section as more gigs are played.
- Music Page
    - As the band are working on releasing their follow-up EP, a new section can be added to the music page for users to select an EP before then taking them to the current article-styled page, specific to that user's selection.
    - The hierarchy of importance would be adhered to here. Albums would follow a categorical release pattern, with newer releases first. 

[Back to top ↑](#the-oversights---band-website)

---
## Structure Plane:
---

The priority of features was discussed within the above plane but to explain further:

**Feature Priority**

The Index page is logically grouped by having high-priority information front and centre, in this case: the music, videos and merchandise. Boosting the discovery and interactivity of high-priority content by the user.

Lower priority information is then divided by relevance into unique pages. These are presented to the user through the navigation bar, which is accessible from each website page. This provides a simple method of navigation while meeting standard user-defined expectations.

### Interaction-Design - IXD
---

The integration of iframes will:
- Expose the user to the band's social media channels. 
- Encourage user interaction with them.
- Convert the user into a follower/subscriber of the platform.

The presence of icons throughout the website serves many purposes:
- Social media icons are highly recognisable. Used throughout the internet they are expected by the user, who immediately knows that interaction will redirect them - via a new browser tab - to the user-expected platform.
- An icon at the bottom of each screen serves as a link back to the top. This is especially important for users on mobile devices who will be scrolling a large single-column layout. The user's experience is thus drastically improved as we save them from the "finger fatigue" of having to scroll back to the top of each section to revisit an element.

Individual pages will serve their functions but adhere to specific features:
- The expected information will be present on each page
    - E.g. - "Shows" contains the galleries of past shows.
- The page's structure will appear relatively linear and be simple for the user to navigate. 
- Sub-pages will be used sparingly to ensure "everything is accessible from everywhere" for each user.
- Information within these pages will be divided into separate columns featuring informative headers and provocative paragraphs, ensuring the user feels encouraged to interact with featured elements.

Information will be categorised into easy-to-access, informative sections. It will adhere to the goal of providing visual clarity:
- Headers will be informative. Setting the user's expectation for the following section's content.
- Paragraphs - when required - will provide information the user would expect. 
    - E.g. "Music" will contain the release date of the record, information about the songs, and information about the band.
- Links will be descriptive and take the user to where they expect.
- The "hover" class shall improve the link's visibility to the user, improving their interactive experience with the website.
- The interaction can be made more intuitive by using a bright contrasting colour like yellow, to clarify visually to the user that they are interacting with a link.

Overall this website will: 
- Be consistent in design, branding and colours.
- Be predictable and well-labelled.
- Meet pre-defined user expectations.
- Ensure that everything has a clear sense of place.
- Require little-to-no learning by the user. 
- Ensure visiting a page once answers all user questions.
- Provide a visual experience adhering to a "show don't tell" philosophy.
- Provide purposeful paragraphs and headings.
- Provide feedback to the user on interaction through the use of the "hover" class.
- Offer "content hinting" - mainly on the index page - to encourage users to scroll downwards and interact with more content.
- Reward the user with the "UP" icon once reaching the bottom of each page, saving the hassle of scrolling back up, while removing the need for a fixed navigation bar that takes up screen real estate. 

[Back to top ↑](#the-oversights---band-website)

---
## Skeleton Plane
---

The website's data will be presented statically as designated in the project description.
Created entirely with the HTML and CSS languages to handle all data.

**User Value**

The UI serves as the system for the user in this case.
It will be kept clean and simple throughout, remaining clutter-free and featuring only essential elements.
It will also provide immediate interaction for the user, whether first time or recurring.

It will allow immediate interaction for the user. 
- Iframes which provide interaction opportunities with external music and videos.
- Icons provide contextual imagery for the user. Enhancing the experience by providing visual metaphors.
- Well sign-posted content and links provide clarity for the user. Providing progressive disclosure for the user, giving them what they need, when they need it.
- Informative headers and paragraphs providing informative prompts and explanations for elements.
- Colourful imagery to draw the user's attention and encourage interaction.
- The priority of information has been factored into the page design to ensure users are met with the most relevant information quickly.
- A simple, navigatable UI ensures users of all ages can comfortably navigate the website on a first visit.
- Each click adds value by leading the user towards their goals, whether that be playing/viewing content or finding information.
- The typography, imagery and hover classes will be used to encourage the user to continue their experience.
- Alerts are used to redirect users to external social platforms to continue their experience of interacting with the band's content. Clarifies situations where a user may be unsure of where to find information providing a positive redirection to their desired location.

These elements will come together with the UI design presented in the next plane to provide users with a positive experience.

**Simplicity of Titles**

The navbar and page names provide the user with a straightforward and expected route to navigate the grouped areas of the website based on their individual needs.

- Interest in the band's recent releases? 
    - Music page.
- Interest in a recent show? 
    - Shows page.
- Are attempting to contact the band with event information? 
    - Contact page.

**Contact Form Layout**

- Name:
- Email:
- Subject:
- Comment:

Following an age-old convention similar to sending an email using a provider, it leads with the name input, followed by email, subject(cc) and ending with a text for the user's comment.

Each input is required by the user for the form to be sent, providing a positive experience for the user by ensuring they are prevented from accidentally sending an incomplete form to the band.

This data is then handled by [FormSubmit](https://formsubmit.co/) and passed onto the band's email, providing the website with a fully functional email form, written entirely in HTML and CSS.

### Wireframes
---

Included below are wireframe designs created with [Balsamiq](https://balsamiq.com/).

This imagery demonstrates the positions of features and elements that compose each page on both mobile devices and computers.
Providing a simplified demonstration of the website's architecture.

Features include:
- Showing how the nav bar conforms to responsive design best practices.
- Displaying example layouts for iframes, headers, icons and text.
- Example layouts for each page and individual section.

<details><summary>Index Wireframe</summary><img src="docs/wireframes/index.png" alt="Index Wireframe"></details>

<details><summary>Music Wireframe</summary><img src="docs/wireframes/music.png" alt="Music Wireframe"></details>

<details><summary>Shows Wireframe</summary><img src="docs/wireframes/shows.png" alt="Shows Wireframe"></details>

<details><summary>Contact Wireframe</summary><img src="docs/wireframes/contact.png" alt="Contact Wireframe"></details>

---
## Surface Plane
---

This plane deals with stylistic choices made during the design of the website.

In the following sections, I will describe how the website creates a positive experience for users through its use of hover effects, predictable navigation, clear content, and minimal non-distracting design.

**Design Philosophies**

The website was designed with a mobile-first approach. Bootstrap and Media Queries were used for the arrangement of elements during resizing.

"Content is king" was a priority in this design strategy. With inviting imagery and iframe elements taking priority over text explanations.

This website is here to compliment the band's work and accomplishments, not overshadow or distract from the content presented. It serves as a promotional hub and as such the branding is strong and the backgrounds are kept to a minimal pallet.

**Comfortable Responsive Navigation**

A notable stylistic choice was ensuring the collapsed "hamburger menu" was floated to the right-hand side of the navigation bar.
The benefit of this is that the majority of users can be assumed as right-handed, this layout choice allows them to navigate the site comfortably, on a mobile device, with one hand.

The social media icons are responsively moved from the footer to the "hamburger menu" for this same reason.
Ensuring users can access them with minimal effort, removing the need to scroll the page down and keeping them in view as users navigate the website.

Iframes will be made responsive using CSS to meet user expectations and fit comfortably on all screen sizes.

**Visual Separation**

Visual separation is achieved between sections of the website through the use of <"HR"> tags to create dividing lines. This simple visual, intuitively tells the user when one section ends and another begins.

Drop shadows were added to the navigation bar and footer to provide a sleek sense of elegance and professionalism to the website. This furthers the visual separation between sections with added an added sense of depth and visual clarity.

This approach is taken one step further on the Music page with Vertical line elements being created in CSS to provide visual column separation.

**Colour Pallet**

A modern, minimalistic design was selected for the website. Utilising black, white and grey for all background colours.

Black and White are timeless choices. They will never be out-of-style and provide ideal contrast between elements, avoiding contrast issues, and reducing overwhelming clutter and visual noise.

Grey is utilised for the navigation menu and footer to help them stand out from other sections.

![Colour Pallet](docs/screenshots/colour_choices.png)

**Hover Colour**

A stylistic choice for the website is utilised when the user's cursor hovers over an interactive link or card. The font colour will change to a bright yellow, with the background colour changing to a black square to provide contrast. This method ensures a user is aware they're currently hovering over an interactive element while positively encouraging them to click/tap.

A further benefit of this minimal colour pallet is that all branding evolves and adapts over time. 
Each album will feature reinventions of their logo, brand colours and imagery. By utilising black and white I've ensured that the website won't need to go through any large revisions. Imagery is updatable and more pages can be added without disrupting the established layout, flow and design.

These colour choices allow the user's eyes to be drawn to selected spots of colour such as:
- The bold Yellow colouration of hovered links
- Imagery added to the website. Which encourages the user to interact with them.
- Ensures visual fidelity of images is maintained as they won't clash with the base design.

**Image Choices**

The colour pallet of the website has been selected to compliment the evocative imagery of the band's albums and merchandise.

The imagery in the merchandise section features colourful backgrounds. Adding personality to the section and encouraging hovering over each card. The user will feel encouraged to approach this section, analyse the items on sale and feel compelled to return to it on future visits.

<details><summary>Album Artwork</summary><img src="assets/images/merch/hello_ep.png" alt="Album Artwork"></details>

<details><summary>Physical CD</summary><img src="assets/images/merch/hello_disc.png" alt="Physical CD"></details>

<details><summary>Sticker Pack</summary><img src="assets/images/merch/sticker_pack.png" alt="Sticker Pack"></details>

<details><summary>T Shirt</summary><img src="assets/images/merch/tiki_shirt.png" alt="T Shirt Design"></details>

A collection of sticker assets are used across pages to give the website a **strong** visual style. They filled blank spaces and helped balance the design of pages, ensuring no columns were left unevenly weighted when compared to neighbours.

Additionally, they add to the culturally appropriate image of a rock band. Serving as a subtle advertisement for the band's merchandise across each page, as this sticker pack is for sale.

**Font / Typography**

The colour "Antique White" was utilised in paragraph text throughout the website, to provide visual distinction between this off-white coloured font and the white background of the website sections.

It is used in conjunction with a black background square to match the style of hovered links, blend seamlessly with the border styling present on cards and contribute to the website's overall style.

The band themselves used different fonts than those present on the website in their initial logo. They however do not own the licensing for these fonts to be used online.

As such [Google Fonts](https://fonts.google.com/) was used to obtain similar, legal versions of fonts that the band can use going forwards on future releases. Setting the tone and branding for their next evolution.

The fonts chosen were:
- [Karla](https://fonts.google.com/specimen/Karla)
    - A multi-weight, sans serif font designed by Jonathan Pinhorn. Designed to be very readable and consistent at each weight. Used for all headers and paragraphs to define the visual style of written text.

- [Rubik Mono One](https://fonts.google.com/specimen/Rubik+Mono+One)
    - A rounded, monospace, sans serif font designed by Hubert & Fischer. Used as it was a bold font resembling the band's current logo, making it eye-catching and a logical choice to differentiate the logo from the header text that used Karla.

**Conforming to Culture**

Short provocative statements are made to the user in paragraph section introductions, such as "'Add Us To Your "Summer Vibes Playlist' On Spotify" and "Live The 'High Life' Right Now!" 

These serve as calls to action and encourage users in a culturally appropriate manner to interact with the following elements.

**Contact Form Interaction**

Once submitted, the form will then redirect the user to a "THANK YOU" page, providing positive feedback that their message has been sent to the band.

The navigation bar remains present to allow the user to continue navigating the website without having to use an external mouse or browser button.

The "THANK YOU" page is hidden from the navigation bar and is only called when a user has sent a message.

Icons are present next to the form inputs to provide clarity and serve as visual metaphors to help convey information.

Contacting the band has been made simpler by removing the default CAPTCHA process. Users of the website can now send messages with fewer steps, improving the process.

**Dependencies**

Bootstrap Java dependencies are placed at the bottom of the body tags. CSS dependencies are kept at the top. 

As webpages are loaded Top-Bottom in the HTML file, this should ensure that the page is loaded quickly and helps to ensure that the user doesn't see an unstyled page. 

---
## Features
---

The following section will be examining how the completed website has met the defined user stories.

**Navigation Bar**

![Colour Pallet](docs/screenshots/colour_choices.png)

The navigation bar is responsive to different screen size and present on all pages. It is made up of simple headers and is intuitive to all users.

The currently active page has it's header left in black and doesn't respond to being hovered over to disuade user interaction. Contrastingly, the inactive pages respond by changing background and text colour to encourage user interaction.

The navigation bar is responsive to all device sizes. On mobile devices the menu is condensed into a drop down menu, freeing up screen real estate and beind represented by a recognisable "hamburger" menu.

The social icons appear in the "hamburger" menu on mobile devices to be readily available for user interaction.

    User Stories met: 5, 14, 17

**Footer**

![Colour Pallet](docs/screenshots/colour_choices.png)

The footer is the only other element present on all pages. As such it is responsive. It contains links to restaurant's profile on the most popular social media, opening hours, contact details and copyrights.
Links to social media are shown as icons, making it easy to find a platform that interests the user. The links open in a new browser tab, so the user stays on the restaurant's website.

    User Stories met: 5, 14, 17

**Index Page**

![Colour Pallet](docs/screenshots/colour_choices.png)


**Music Page**

![Colour Pallet](docs/screenshots/colour_choices.png)


**Shows Page**

![Colour Pallet](docs/screenshots/colour_choices.png)


**Contact Page**

![Colour Pallet](docs/screenshots/colour_choices.png)


**Thanks Page**

![Colour Pallet](docs/screenshots/colour_choices.png)



[Back to top ↑](#the-oversights---band-website)

---
## Testing
---

**Validation Tests**

Info goes here.

**Screen Reader**

Info goes here.

**Different browsers & devices**

Info goes here.

[Back to top ↑](#the-oversights---band-website)

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

5. Brand text was forcing the hamburger menu navbar onto the line below on smaller devices (< 450px). Bootcamp solutions
seemed to remove my icon as well leaving the bart with no branding and moving the burger menu to it's default position of floating to the left. I decided the simplist method would be to use a media query to hide just the brand text on smaller devices. Leaving the logo present in the nav bar - to maintain branding - while keeping the nav burger menu on the right hand side where users would expect it to be.

        /*--- Prevents the Brand text from pushing the navbar to the line below. Disappears before hand, leaving the logo visible*/
        @media screen and (max-width: 450px) {
            .navbar-brand{
                width: 0;
                font-size: 0;
            }
        }

[Back to top ↑](#the-oversights---band-website)

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

[Back to top ↑](#the-oversights---band-website)

---
## Deployment
---

[Back to top ↑](#the-oversights---band-website)

---
## Acknowledgements
---

With thanks to:
- My fellow "Oversights" for trusting me with this task and providing helpful feedback throughout.

- My family and friends - for keeping me on task and providing a helpful eye or a pair of testing hands when needed.

- Code Institute & it's community at large, for providing me with the necessary skills, knowledge and guidance to pull this project off.

[Back to top ↑](#the-oversights---band-website)

---