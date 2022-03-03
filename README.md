# Frontend Mentor: Sunnyside Agency Landing Page

<p align="center">
<img src="https://res.cloudinary.com/dxzcdb0pm/image/upload/v1646190533/fem-compilation/sunnyside_p6qsru.png" alt="Sunnyside Agency Landing Page Preview" />
</p>
<br />
<p align="center">
  <a href="https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef/hub/sunnyside-agency-landing-page-RoP8ukMov">View Challenge</a> | <a href="https://goofy-wozniak-4b3815.netlify.app/">View Live Site</a>
</p>

<br />

Users should be able to:
- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

---


## Overview

To give myself a bit of a challenge, I built this React app from scratch. I used Parcel instead of webpack, though I think it could be cool to either redo this project with Vite or webpack. I ran into a couple of issues with deployment, but it all came down to some issues in my Parcel config and the wrong plugin for static files. I eventually sorted out these issues and was able to deploy it without too many issues.

While getting the styling sorted, I got to learn more about the `aspect-ratio` property, which I hadn't really used before in the past. It works fine, but has no IE support. There are of course, a couple of hacks I learned in the process of making this site that achieve similar effects but require more markup (like for the padding hack, for instance).


## Built with

- React (from scratch)
- Parcel
- styled-components
- styled-reset (for CSS reset)
- Hosted with Vercel
