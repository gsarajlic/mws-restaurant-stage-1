# Restaurant Reviews
---
## Table of Contents

<<<<<<< HEAD
## Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality. 

### What do I do from here?

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 
=======
- [Background](#background)
- [Installation](#install)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Background

In this project, a static restaurant reviews website is converted into one that is responsive. In addition, accessibility is implemented, so the site is ready for screen reader and/or keyboard use.
Also we had to implement service worker, to allow offline experience.
>>>>>>> google-maps

### Installation

<<<<<<< HEAD
2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3. Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4. Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information. 

### Note about ES6
=======
After cloning or downloading this project, you will need a local server to run
it. The simplest method is using Python's simple HTTP server.
1. Install Python 2.x or Python 3.x from the [Python website](https://www.python.org/downloads/)
2. In your terminal or command line, navigate to the directory containing this project
3. If you installed Python 2, type `python -m SimpleHTTPServer 9100` or, if you
installed Python 3, type `python3 -m http.server 3000`

### Usage
>>>>>>> google-maps

To see the Google Maps served by the website, you need to get a [Google Maps API
Key](https://developers.google.com/maps/documentation/javascript/get-api-key)
and substitute the `YOUR_GOOGLE_MAP_API_KEY` text with your own API key in both the index.html and the restaurant.html files.

Then, with your server running, point your browser to `http://localhost:9100`
and enjoy!

You can search restaurants in New York by neighborhood or by cuisine. You can learn each restaurant's address and opening hours, find the restaurant on the
map, and read the reviews other customers wrote.

### Credits
The starter code for the static restaurant reviews website is from [Udacity](https://github.com/udacity/mws-restaurant-stage-1)
Also I would like to mention that Mohammed Riaad study jams heped a lot on this project. Thank you !
