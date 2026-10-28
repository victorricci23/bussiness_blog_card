<!-- Project README for Business Blog Card -->

<h1 align="center">Business Blog Card | devChallenges</h1>

<div align="center">
  Solution for the
  <a href="https://devchallenges.io/challenge/business-blog-card" target="_blank">Business Blog Card</a>
  challenge from <a href="https://devchallenges.io" target="_blank">devChallenges.io</a>.
</div>

<div align="center">
  <h3>
    <a href="https://devchallenges.io/challenge/business-blog-card">Challenge</a>
  </h3>
</div>

## Table of Contents

- [Overview](#overview)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Built with](#built-with)
- [Features](#features)
- [Author](#author)

## Overview

![screenshot](https://media.discordapp.net/attachments/1464634656463786118/1565094732651298887/Captura_de_tela_de_2026-10-28_17-07-27.png?ex=6ae3a78e&is=6ae2560e&hm=4a99e210850258c82b85b8ba54c781b297e089a71d3a7f5bfac4cf62672d0348&=&format=webp&quality=lossless)

This project is a simple webpage featuring a business blog card. The card includes a main image, a title, a short description, and the author's information.

The layout was built with HTML and CSS, including responsive adjustments for larger screens.

### What I learned

While developing this project, I practiced:

- **Flexbox:** I used `display: flex` and `flex-direction: column` on the `body` to arrange the page vertically, and `margin-top: auto` on `.author-info` to keep the author information at the end of the available space.
- **CSS positioning:** I used `position: relative` on `.card-top` and `position: absolute` on the decorative image to overlay the wave element on top of the main image.
- **Box model:** I applied `box-sizing: border-box` globally to make element dimensions easier to control.
- **Responsive design:** I used `max-width: 100%` on the card and a media query to adjust its margins on screens with a minimum width of `1024px`.
- **Flex-wrap:** I set `flex-wrap: wrap` on the author section to allow its elements to wrap onto another line when needed.
- **Typography:** I imported the Lato and Poppins fonts from Google Fonts and used them in different parts of the card.

### Useful resources

- [MDN — CSS Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout) — a reference for arranging elements with Flexbox.
- [MDN — Media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries) — a reference for applying styles based on screen width.
- [Google Fonts](https://fonts.google.com/) — used to import the Lato and Poppins fonts.

## Built with

- HTML5
- CSS3
- Flexbox
- Media queries
- Google Fonts (Lato and Poppins)

## Features

- Business blog card with an image, title, and description.
- Author section with an avatar, name, and job title.
- Decorative image layered over the main image.
- Rounded corners and a box shadow.
- Layout adjustments for different screen widths.
- Footer with author and challenge credits.

## Author

- Coded by **Victor C. Ricci**
- GitHub [@victorricci23](https://github.com/victorricci23)
