## Project Name & Pitch

Palatial Revimeo

An application used to filter data from Vimeo.com based videos, built with React, Redux, JavaScript, and CSS. User can favorite songs.

## Project Status

This project is currently in development. Users can search for videos using Vimeo API, and display hash tags.

## Project Screen Shot(s)

[Screen Shot](http://imgur.com/a/p5mVj)

## Installation and Setup Instructions

#### Example:  

Clone down this repository. You will need `node` and `npm` installed globally on your machine.  

Installation:

`npm install`  

To Run Test Suite:  

`npm test`  

To Debug:

`node debug server.js ; repl`

To Start Server:

`VIMEO_CLIENT_SECRET=KMjW6p2aO3UI/yR7+C8fO9YFYeVRSfl4c9zK4fZWPOb5pmqS9gG8rtpO8Ntw91d8hJ5w1JZdP1HWdK4PxIiwDP0aU0dPhy/8VKja9G02t835aWHaXArrWowLr8i9WtGq node server.js`  

To Visit App:

`localhost:9000/`  

## Reflection

  - What was the context for this project? (ie: was this a side project? was this for Turing? was this for an experiment?)
  - What did you set out to build?
  - Why was this project challenging and therefore a really good learning experience?
  - What were some unexpected obstacles?
  - What tools did you use to implement this project?
      - This might seem obvious because you are IN this codebase, but to all other humans now is the time to talk about why you chose webpack instead of create react app, or D3, or vanilla JS instead of a framework etc. Brag about your choices and justify them here.  

## Reflection:  

This was a 2 week long project built during my third module at Turing School of Software and Design. Project goals included using technologies learned up until this point and familiarizing myself with documentation for new features.  

Originally I wanted to build an application that allowed users to pull data from the Genius API. I started this process by using the `create-react-app` boilerplate, then adding `express` `react-router` and `redux`.  

One of the main challenges I ran into was Authentication. This lead me to spend a few days on a research spike into OAuth, Auth0. Due to a lack of good data inside of the Genius API (No Lyrics!), I had to pivot to using a better API, like the Vimeo API.

The technologies used in this project are React, React-Router, Redux, VanillaJS, JSX, and CSS. I chose to use the `create-react-app` boilerplate to minimize initial setup and invest more time in diving into server-side-rendering, and building a reusable Oauth2 boilerplate for future endeavors with new API calls. I enjoy `create-react-app`, if only for its great read-me, and cohesive design, and I plan on continuing to use it in the future.

For my next self-directed project I've learned that I want to dream up a product first, set my aim high, and then look for the tools to get it done, be that a external API, or a rest API. 
