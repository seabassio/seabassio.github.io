---
layout: project
type: project
image: img/manoapulselogo.PNG
title: "Manoa Pulse"
published: true
labels:
  - NextJS
  - Bootstrap
  - Vercel
  - PostgreSQL
summary: "A web application designed for students to update and keep track of how busy each popular spot is on campus!"
---

Manoa Pulse was the final project for my Software Engineering I class. I helped plan, execute, and upkeep several parts of the project while it was in development.

<div class="text-center p-4">
  <img width="400px" 
       src="../img/heatmap.PNG" 
       class="img-thumbnail" >
    <img width="400px" 
       src="../img/pulse-feed-M3.PNG" 
       class="img-thumbnail" >
</div>

This was an interesting project to work on because it was my first real web application that used already existing frameworks. It not only needed to be updated, but also needed maintenance to keep the site running as it should have been. Using software like Prisma and Vercel was a pain at times, but eventually I grew to see the usefulness in having software platforms already built in that regard.

Here are the parts that I contributed in during the devlelopment of this project:

- Coming up with the idea for the Heat Map of the campus took some ironing out. As all of us had different ideas on what the project should have been, we had to meet in the middle and design an app that could actually have use in the future. We took the ideas of studying, crowd-sourced data, and a unique interface, and came up with the idea of a visual map to show how busy the entire campus is.
- I mainly worked the backend, learning how to work with the database and to keep everything in sync. For this project we used a Prisma PostgreSQL database linekd up to a Vercel deployment. This allowed us to obtain data from anyone who used the site and update it accordingly. Although I had some trouble working with Prisma in particular, the team eventually figured it out and we were able to add features that we did not know we had the ability to.
- I also helped with small UI elements such as the comment section and the submit update page. Working on UI with the NextJS framework is interesting because of how components work. With components, you can place complex UI elements by simply calling them like a function in the body of your page.tsx file. It can allow for some very useful tools to be deployed in multiple parts of the UI, such as a sidebar.

<a href="https://manoa-pulse-one.vercel.app/">Vercel Deployment of app</a>
<a href="https://manoa-pulse.github.io/">Link to github.io page</a>

<div class="text-center p-4">
    <img width="600px" 
       src="../img/landing-page.PNG" 
       class="img-thumbnail" >
</div>
