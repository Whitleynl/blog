---
layout: post
title:  "Ideating"
date:   2024-09-29 00:00:24 -0400
categories: update
---
progress: designed the database --> then realized there's no way I wouldn't returning to it time and time again for redesigns. So I pared it down to bare essentials --> Users and their Dreams.
I had already decided to use Python/Django on the back so I set it up, got it connected to the MySQL database and then got React/Tailwind going on the front. 
I was curious about cloud deployment (and was getting tired of repeatedly running the the servers manually) so I decided to go ahead and deploy. 
Little research --> conclusion: Vercel hosts the frontend and Heroku hosts the backend. They both have free or dirt cheap tiers that offer what I need with easy set up and maintenance. 
Hopefully the aquaintence with cloud deployment will also make it easier to learn AWS later on. 
I built a minimal little UI and added DreamSubmit/Search/Delete functions. This was all working before deployment and now the frontend can't connect to the database. 
That brings us up to speed. Can't wait to get thing working again so I can start thinking about more features. 

nathan