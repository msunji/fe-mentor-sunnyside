# Frontend Mentor: Sunnyside Agency Landing Page

Here's my take on this [challenge](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef/hub/sunnyside-agency-landing-page-RoP8ukMov);

## Overview

For this challenges, users need to be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

Here's the desktop version:

![Desktop Version](https://github.com/msunji/fe-mentor-sunnyside/blob/main/static/desktop-preview.png)

<!--
And here's how it looks like on mobile
![Mobile Version](https://github.com/msunji/fe-mentor-sunnyside/blob/main/static/mobile-preview.png) -->

This took a bit longer than I'd like to admit. I didn't bootstrap this with CRA, and opted to make this from scratch with Parcel instead of Webpack. Not to mention, I probably focussed a bit longer on the aspect-ratio/row-col sizing for some of the grid cells. Overall, I did learn more about the `aspect-ratio` property, which I hadn't really used before in the past. It works fine, but has no IE support. There are of course, a couple of hacks I learned in the process of making this site that achieve similar effects but require more markup (like for the padding hack, for instance).

On a somewhat different note, I also ran into a number of issues while deploying this site, but managed to sort it out in the end. It was a combination of using the wrong plugin for static files and a couple of issues in my `package.json` config for Parcel.

## Built with

- React (from scratch)
- Parcel
- styled-components
- styled-reset (for CSS reset)
- Flexbox
- CSS Grid
- Hosted with Netlify
