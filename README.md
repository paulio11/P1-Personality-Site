# Kyle Bosman - Internet Personality Website

[Link to live GitHub deployment](https://paulio11.github.io/project-1/)

![Website responsive screenshot](https://paulio11.github.io/project-1/assets/images/readme/amiresponsive.png)

## Introduction
This website serves as a first point of contact and information for YouTuber and Twitch stream Kyle Bosman.

A problem with the modern internet is that there are so many services one idividual may be signed up for and using at the same time - all for different purposes and reasons. Sites such as Twitter, Facebook, Instagram, Patreon, YouTube and Twitch. When you google someone you get hundreds of results all taking you to different places where you may or may not find the information you are looking for.

![Google result count for Kyle Bosman](https://paulio11.github.io/project-1/assets/images/readme/googleresult.png)

The goal of this project is was to make a central location where you can find exacatly what you've been looking for. A short summary about the person and showcases of the work they do and links to follow to all corners of the internet where they might have public profiles/pages. Enabling you to get to where you need to be.

Since googling my own name hopefully should bring up zero results I have taken on the identity of a lesser known internet celebrity to serve as my example. In particular - YouTuber and Twitch streamer Kyle Bosman. You can find more information about him in the website I have put together for this project. There you will see an overview of the things he does and where you can find that work. From his YouTube series [Delayed Input](https://www.youtube.com/playlist?list=PLXjlB8AgMh8QuT0_ao9vaZlI1jf2U4SGS) to his streaming schedule on [Twitch](https://www.twitch.tv/kylebosman), as well as a little history of what he has been up to recently.

The site was not made as a fan site, but more as If I were the person himself and required someplace to be my own corner of the internet.

**This is in no way associated with Kyle and all the videos linked to and embeded on the website belong to him.**

This was my first milestone project required to complete my Diploma in Full Stack Software Development at [The Code Institute](https://codeinstitute.net). This website required me to showcase my newly learned HTML and CSS skills by creating something that was both useful to the end user and responsive in design so it could scale to any resonable display size.

## The User Experience
A user for this website could fall into one of the following categories:
- A fan of Kyle.
- A new future business partner.
- A new potential fan.

### User Goals

#### As a fan
- I would want to see the latest updates about Kyle.
- I would want to see the newest episode of his show Delayed Input.
- I would want to find out when he will next be streaming on Twitch, and have a link straight to that stream.
- I might want to submit a piece of art I have made to his weekly art show.

#### As a future business partner
- I would want to see a short history about Kyle and what he does.
- I would want to be able to easily get in touch with Kyle.

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

![Site Map](https://paulio11.github.io/project-1/assets/images/readme/sitemap.png)

### Wireframe

[Balsamiq for Desktop](https://balsamiq.com/wireframes/) was used ahead of developement to plan the basic skelton of the three pages.

## Design

### Colour Scheme

The colour scheme was chosen based on the other websites in which Kyle publishes his content - namely Twitch and YouTube. With the hope that the colours of red (representing YouTube) and purple (representing Twitch) help tie all his work together whilst also highlighting the importance of those other websites. This provices a cohesive experiece if the user should choose to visit one of these external websites following links on the page. The rest of the content ins in a simple black and white. The four colours together help define each section of the page as well as maintaining visual accessibility due to their high contrast. 

#### Colour Palette

![Colour Palette](https://paulio11.github.io/project-1/assets/images/readme/palette.jpg)

### Typography

Fonts are imported from [Google Fonts](https://fonts.google.com). I chose [Fredoka One]() for both the `<h1>` and `<h2>` headings - used as the main title of the page and the titles of each main section. [Kanit]() for any less important titles within a section as it better fits with the body text. The body text is [Anek Malayalam]() as it is clear at all font sizes and fits the moder look I was aiming for. To contrast from the rest of the site [Staatliches]() in `uppercase` was used for the `<header>` and `<footer>` navigation links.

### Images and Video

Social website icons are part of the icon library of [Font Awesome](). The text logos for both YouTube and Twitch are taken from their websites brand assets pages.

The video highlighting some popular Kyle Bosman videos was edited together by YouTuber [Dominic Barlow](). I ran it through an online conversion tool to lower the file size by using the .webm format. It's smaller file size (14mb) and quality better suits it's place on a home page.

The Delayed Input logo is used on both the [Patreon Page]() for the show and as part of each episodes introduction. It was designed and created by [Scott Asquith](http://scottasquith.com). It is used as a `background-image` in the [Delayed Input](https://paulio11.github.io/project-1/#delayed-input) section.

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

The [Contact](https://paulio11.github.io/project-1/contact-me.html), [Watch Live](https://paulio11.github.io/project-1/watch-live.html) and [Home](https://paulio11.github.io/project-1) pages all have a consistent style. Built from the ground up to be responsive and viewable on all screen sizes with a `min-width: 300px`.

Each page contains the following common features:
- The main page `<header>`.
    - A area right at the top of the page with links to the sections within the main index.html page as well as contact-me.html and watch-live.html.
    - This navigation menu is a responsive `display: flex;` set to `flex-wrap: wrap;` so it adjusts to fit smaller screen sizes or resized windows.
- The page title.
    - A `<h1>` element.
- Similar margins and paddings to create consistent spacing.
    - Using a variable in CSS during development to make it easy to adjust manually or for creating `@media` queries.
    - `--padding: 2.5%;`.
- A `<footer>` bar containing a line of copy-write text and social links with icons from [Font Awesome]().
    - Set to `float: left;` and `float: right;`.

Neither the `<header>` or `<footer>` are fixed to the top/bottom of the screen as I believed it would have taken up too much screen space - especially on a smaller device. To remedy the navigation issues casued on [home page](https://paulio11.github.io/project-1) I added a simple javascript *scroll back to top* button. The code used was taken from [W3 Schools](https://www.w3schools.com/howto/howto_js_scroll_to_top.asp) as my course has not yet touched on javascript thus far. It is styled using CSS to match the overall look and feel of the website.