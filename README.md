# Supernatural_events_tracker

## Overview
The Supernatural Events Tracker, aka 'paranormal.DB', was a week long, Full Stack Javascript project undertaken by [Alastair Kane](https://github.com/alistairkane92), [Chad Tung](https://github.com/chad-tung/), [Scott Murray](https://github.com/smrr723) and [Alex Smith](https://github.com/axolotlquestions).

### MVP
The project specification was to build a Full Stack (Vanilla) Javascript Webapp, and in it's simplest form, users should be able to:
* Input event data (Title, Date, Description, Location via marker drop) into a web form
* Browse through a list of events, by using a list view, or a map view

To meet these requirements, we used vanilla Javascript to render different views to our index.html file, between the header and footer sections, using an onClick event listener to render the different components.  For data management, we used ExpressJS with MongoDB as our database and simultaneously pulled our data from an on site JSON API which we created at '/api/events'.

### Agile Development
We tried to incorporated Agile Development methodologies into our project from Day 1.  Typically we would begin our days with an informal 'stand up' and briefly review what we had done the previous day, and most importantly, a realistic target of what we wanted to accomplish by the end of that day.

The majority of our project, certainly the MVP, was mob programmed.  Whilst this may have been slightly slower than branching off individually earlier, we found that it left us with fewer bugs, and less time spent on any issues that did arise during development.  We used a tool called Atom Teletype (https://atom.io/packages/teletype), without which our mob programming sessions would not have been possible.


## Built Using
* TeleType (https://atom.io/packages/teletype)
* Vanilla JavaScipt (http://vanilla-js.com/)  
* HTML5 (https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)  
* CSS3 (https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3)  
* JSON (https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)  
* Express (https://expressjs.com/)  
* Mocha Testing Suite (https://mochajs.org/)  
* Nodemon (https://nodemon.io/)  
* Webpack Bundler (https://webpack.js.org/)  
* Mongo Database (https://docs.mongodb.com/) - to produce a custom Venue API  
* Node.js (https://nodejs.org/en/)  
* Google Maps API (https://developers.google.com/maps/documentation/javascript/) 