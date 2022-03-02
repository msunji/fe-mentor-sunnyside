# Frontend Mentor: Sunnyside Agency Landing Page

<p align="center">
<img src="https://res.cloudinary.com/dxzcdb0pm/image/upload/v1646190533/fem-compilation/sunnyside_p6qsru.png" alt="Sunnyside Agency Landing Page Preview" />
</p>
<br />
<p align="center">
  <a href="https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef/hub/sunnyside-agency-landing-page-RoP8ukMov">View Challenge</a> | <a href="https://goofy-wozniak-4b3815.netlify.app/">View Live Site</a>
</div>

<br />

Users should be able to:
- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

---


## Overview

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
