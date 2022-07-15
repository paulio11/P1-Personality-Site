# Kyle Bosman - Internet Personality Website

[Link to live GitHub deployment](https://paulio11.github.io/project-1/)

![Website responsive screenshot](https://paulio11.github.io/project-1/documentation/amiresponsive.png)

## Introduction
This website serves as a first point of contact and information for YouTuber and Twitch streamer Kyle Bosman.

A problem with the modern internet is that there are so many services one individual may be signed up for and using at the same time - all for different purposes and reasons. Sites such as Twitter, Facebook, Instagram, Patreon, YouTube and Twitch. When you google someone you get hundreds of results all taking you to different places where you may or may not find the information you are looking for.

![Google result count for Kyle Bosman](https://paulio11.github.io/project-1/documentation/googleresult.png)

The goal of this project was to make a central location where you can find exactly what you've been looking for. A short summary about the person and showcases of the work they do and links to follow to all corners of the internet where they might have public profiles/pages. Enabling you to get to where you need to be.

Since googling my own name hopefully should bring up zero results I have taken on the identity of a lesser known internet celebrity to serve as my example. In particular - YouTuber and Twitch streamer Kyle Bosman. You can find more information about him in the website I have put together for this project. There you will see an overview of the things he does and where you can find that work. From his YouTube series [Delayed Input](https://www.youtube.com/playlist?list=PLXjlB8AgMh8QuT0_ao9vaZlI1jf2U4SGS) to his streaming schedule on [Twitch](https://www.twitch.tv/kylebosman), as well as a little history of what he has been up to recently.

The site was not made as a fan site, but more as If I were the person himself and required someplace to be my own corner of the internet.

**This is in no way associated with Kyle and all the videos linked to and embedded on the website belong to him.**

This was my first milestone project required to complete my Diploma in Full Stack Software Development at [The Code Institute](https://codeinstitute.net). This website required me to showcase my newly learned HTML and CSS skills by creating something that was both useful to the end user and responsive in design so it could scale to any reasonable display size.

## The User Experience
A user for this website could fall into one of the following categories:
- A fan of Kyle.
- A new future business partner.
- A new potential fan.

### User Goals

#### As a fan
- I would like to see the latest updates about Kyle.
- I would like to see the newest episode of his show Delayed Input.
- I would want to find out when he will next be streaming on Twitch, and have a link straight to that stream.
- I might want to submit a piece of art I have made to his weekly art show.

#### As a future business partner
- I would like to see a short history about Kyle and what he does.
- I would like to be able to easily get in touch with Kyle.

#### As a new potential fan
- I want a place to see the newest and classic video games streamed.
- I want to hear a quirky new take on the latest gaming news of the week.

#### As any/every user
- I want an easy to navigate site where I can get to the page or information I want in just a single click.
- I want a website that works and displays information correctly whether I'm on my phone, tablet, or computer.

## Development Planning

To meet the requirements of the potential users the website will have to have the following sections/pages:
- Introduction
- Delayed Input
- Schedule
- Games I've Played
- Watch Live
- Contact Me
- Social Links

Functionally the website should be:
- Relevant and informative
- Accessible
- Easy to navigate
- Responsive

### Site Map

![Site Map](https://paulio11.github.io/project-1/documentation/sitemap.png)

### Wireframe

[Balsamiq for Desktop](https://balsamiq.com/wireframes/) was used ahead of development to plan the basic skeleton of the three pages. You can download my wireframe file [here](https://paulio11.github.io/project-1/documentation/wireframe.bmpr).

![Website wireframe](https://paulio11.github.io/project-1/documentation/wireframe.jpg)

## Design

### Color Scheme

The color scheme was chosen based on the other websites in which Kyle publishes his content - namely Twitch and YouTube. With the hope that the colors of red (representing YouTube) and purple (representing Twitch) help tie all his work together whilst also highlighting the importance of those other websites. This provides a cohesive experience if the user should choose to visit one of these external websites following links on the page. The rest of the content is in a simple black and white. The four colors together help define each section of the page as well as maintaining visual accessibility due to their high contrast.

#### Color Palette

![Color Palette](https://paulio11.github.io/project-1/documentation/palette.jpg)

### Typography

Fonts are imported from [Google Fonts](https://fonts.google.com). I chose [Fredoka One](https://fonts.google.com/specimen/Fredoka+One) for both the `<h1>` and `<h2>` headings - used as the main title of the page and the titles of each main section. [Kanit](https://fonts.google.com/specimen/Kanit) for any less important titles within a section as it better fits with the body text. The body text is [Anek Malayalam](https://fonts.google.com/specimen/Anek+Malayalam) as it is clear at all font sizes and fits the modern look I was aiming for. To contrast from the rest of the site [Staatliches](https://fonts.google.com/specimen/Staatliches) in `uppercase` was used for the `<header>` and `<footer>` navigation links.

### Images and Video

Social website icons are part of the icon library of [Font Awesome](). The text logos for both YouTube and Twitch are taken from their websites' brand assets pages.

The video highlighting some popular Kyle Bosman videos was edited together by YouTuber [Dominic Barlow](). I ran it through an online conversion tool to lower the file size by using the .webm format. Its smaller file size (14mb) and quality better suits its place on a home page.

The Delayed Input logo is used on both the [Patreon Page]() for the show and as part of each episode's introduction. It was designed and created by [Scott Asquith](http://scottasquith.com). It is used as a `background-image` in the [Delayed Input](https://paulio11.github.io/project-1/#delayed-input) section.

Video game cover art is used in the [Games I've Streamed](https://paulio11.github.io/project-1/#games-ive-streamed). Game cover art is property of the video game's publisher in most cases, but these are often freely used on websites such as [Twitch](https://www.twitch.tv) and online stores.

| Game | Publisher |
| ----------- | ----------- |
| TMNT Shredder's Revenge | DotEmu |
| Rifftrax the Game | Wide Right Interactive |
| Kirby and the Forgotten Land | Nintendo |
| Pokémon Legends Arceus | Nintendo |
| Final Fantasy XIV Heavensward | Square-Enix |
| Monster Hunter Rise | Capcom |
| Final Fantasy IX | Square-Enix |

## Features

The [Contact](https://paulio11.github.io/project-1/contact-me.html), [Watch Live](https://paulio11.github.io/project-1/watch-live.html), [Home](https://paulio11.github.io/project-1), and error pages all have a consistent style. Built from the ground up to be responsive and viewable on all screen sizes with a `min-width: 300px`.

Each page contains the following common features:
- The main page `<header>`.
    - An area right at the top of the page with links to the sections within the main index.html page as well as contact-me.html and watch-live.html.
    - This navigation menu is a responsive `display: flex;` set to `flex-wrap: wrap;` so it adjusts to fit smaller screen sizes or resized windows.
- The page title.
    - A `<h1>` element.
- Similar margins and paddings to create consistent spacing.
    - Using a variable in CSS during development to make it easy to adjust manually or for creating `@media` queries.
    - `--padding: 2.5%;`.
- A `<footer>` bar containing a line of copy-write text and social links with icons from [Font Awesome]().
    - Set to `float: left;` and `float: right;`.
    - Placed at the bottom of the viewport using `display: flex;`, `flex-direction: column;`, and `flex-grow: 1;` on a container `<div>` that holds the page content above the `<footer>`.
- Responsive font sizes suitable for all widths using `clamp`.

Neither the `<header>` or `<footer>` are fixed to the top/bottom of the screen as I believed it would have taken up too much screen space - especially on a smaller device. To remedy the navigation issues caused on the taller [home page](https://paulio11.github.io/project-1) I added a simple javascript *scroll back to top* button. The code used was taken from [W3 Schools](https://www.w3schools.com/howto/howto_js_scroll_to_top.asp) as my course has not yet touched on javascript thus far. It is styled using CSS to match the overall look and feel of the website. Using the css rule `scroll-behavior: smooth;` allows the user to see where they are navigating to.

_**[Home Page](https://paulio11.github.io/project-1)**_

The home page is split into four sections, reachable by either scrolling down the page or using the navigation links in the header. The content is displayed as a single column on smaller devices but changes to `display: grid;` at higher screen widths.
- _Introduction_ - A column with the title, brief introduction text explaining who Kyle is, and a `<video>` showing highlights. Changes to a grid to show content better at larger widths. Title on top, paragraph and video side by side.
- _Delayed Input_ - Similar in structure to the introduction section, showing an embedded YouTube video in a single column and smaller screen widths, changing to a grid at larger screen widths.
- _My Schedule_ - A `display: flex;` div showing cards for each day that Kyle does something. Four cards in total displaying as a column, then a 2x2 arrangement, up to a 1x4 line at larger screen widths. To avoid an unpleasant looking line of 3 cards then a line with a single card at widths between where 2x2 and 1x4 work I used a `@media` query to change the flex direction - see video below.
- _Games I've Played_ - My most complex section. Starting as a single column of four games Kyle has recently played. Showing off game box art, a title with links to YouTube, and a table underneath giving those games a fake score along with the date the game was played. All styled to look like a single cohesive card. At larger screen widths this changes to a 2x2 arrangement, then a 3x2 showing more cards than before, then finally a grid showing a row with a paragraph and 3 games, followed by another row with 5 games - again showing more than before. This was achieved using a combination of hiding larger elements with `display: none;` and targeting and hiding specific children using:
    ```
    #game-list-1 .game-card:nth-of-type(n+5) {
        display: none;
    }
    ```
- A javascript back to top button.

<details>
<summary>Home page responsive layout video</summary>

![Home page responsive layout video](https://paulio11.github.io/project-1/documentation/XXXXXXXX)

</details><br>

_**[Watch Live](https://paulio11.github.io/project-1/watch-live.html)**_

This is where visitors to the website can go to watch Kyle if he is live, or take part in his Twitch chat. The main content of this page is two `<iframe>` elements. Displaying side by side at larger screen widths and above and below each other at smaller screen widths. The code used to make this layout responsive was based on code by [Phil Nash](https://philna.sh/blog/2020/03/23/responsive-twitch-embed/).

<details>
<summary>Watch Live page responsive layout video</summary>

![Watch Live page responsive layout video](https://paulio11.github.io/project-1/documentation/XXXXXXXX)

</details><br>

_**[Contact Me](https://paulio11.github.io/project-1/contact-me.html)**_

The contact page has a form the user can use to get in touch with Kyle, and a paragraph. They appear side by side at larger screen widths and a single column at lower screen widths.
- The paragraph has brief instructions for the user, using bold text where necessary, and a note explaining the *asterix found in the form.
- The red asterix is a `<span>` with a class styled `color: red;`. This is displayed within a `required` input's `<label>` element.
- The form is made up of three self explanatory inputs. Name, email, and the message itself - all required. A subject field with a choice of three radios. Two buttons styled to match, one for clearing the form, the other to send the message. Finally a file input used to select and upload an image/video for a user wanting to submit art.
- The label for the file input has been styled to look like a button in order to fit in the with style of the form, to achieve this I had to hide the button itself.


<details>
<summary>Contact Me page responsive layout video</summary>

![Contact Me page responsive layout video](https://paulio11.github.io/project-1/documentation/XXXXXXXX)

</details><br>

_**[Error page 404 - Page not found](https://paulio11.github.io/project-1/404.html)**_

Just in case the user tries to visit a url that does not exist this 404 error page is displayed. It has the same basic structure as the other pages, header, title, footer etc - but the main body is just a simple error message and a **go back** button so the user can return to where they were.

_**[Error page 500 - Internal server error](https://paulio11.github.io/project-1/500.html)**_

Same as the 404 page besides the heading and text to let the user know there has been a server error.

### Unimplemented Features

If I had more time I would have loved to have implemented the following:
- A contact form confirmation page instead of just directing to the Code Institute form dump.
- Due to hiding the file input on the contact form (to match style) there is no longer feedback showing a file has successfully been selected. Would love to have researched this more and added something to show this in the button's absence.
- A hamburger menu for the header navigation menu. It wraps and covers 2 or 3 lines at lower screen widths which looks okay but not great. This is probably something I can come back and add once I start learning more about javascript.
- A gallery page based on the one in the [Love Running](https://github.com/paulio11/love-running) walkthrough project. This would have been a great way to show off some of the art Kyle receives and showcases weekly on his streams.

## Bugs and Other Development Issues

**Responsive design** - I started designing this website with a desktop sized screen width in mind. This resulted in much more work when writing `@media` queries to then adapt it to all smaller width devices. To avoid the extra work this caused I went back to the drawing board and built the website from the ground up with a mobile first design in mind. This drastically reduced the amount of CSS styles I had to write.

**Videos on the website** - To fit with the rest of the style, I wanted the videos (both YouTube embedded and `<video>` elements) to have a `border-radius`. Unfortunately this had to be removed as it would cause a flicker effect over the videos as the browser tried to render the curved corners - so it was removed.

**Home page navigation** - The first four links in the navigation menu all lead to a `<section>` on the home page. Due to the navigation bar not being fixed to the top of the viewport, a user might find themselves wondering where they have ended up as the browser suddenly scrolls to a lower point of the page. To remedy this I added in a *scroll back to top* button. The code used was taken from [W3 Schools](https://www.w3schools.com/howto/howto_js_scroll_to_top.asp) and then styled to fit. Research led me to the css rule `scroll-behavior: smooth;`, which helps remove the sense of the user being lost when the page suddenly scrolls to a section.

**File submission on contact form** - I found the `<input type="file">` button unable to be styled to match the rest of the form and website. To make it fit I set it to be hidden with the css rule `display: none;` and instead styled the `<label>` to look like a button. This solves the miss-matching style issue but unfortunately means that the user doesn't receive feedback showing a selected file until they submit the form.

## Technologies

### Main Languages Used
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/CSS) - You can see my stylesheet [here](https://github.com/paulio11/project-1/blob/main/assets/css/style.css).

### Other
- [Google Fonts](https://fonts.google.com/)
- [Font Awesome](https://fontawesome.com/)
- [GitHub](https://github.com/)
- [GitPod](https://www.gitpod.io/)
- [Balsamiq](https://balsamiq.com/)
- [Code Institute Student Template](https://github.com/Code-Institute-Org/gitpod-full-template)
- [Affinity Photo](https://affinity.serif.com/en-gb/photo/)
- [Veed.io](https://www.veed.io/convert/video-converter)

## Testing

## Deployment

## Credits

