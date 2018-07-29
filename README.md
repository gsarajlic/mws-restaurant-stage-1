# Restaurant Reviews
---
## Table of Contents

- [Background](#background)
- [Installation](#install)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Background

In this project, a static restaurant reviews website is converted into one that is responsive. In addition, accessibility is implemented, so the site is ready for screen reader and/or keyboard use.
Also we had to implement service worker, to allow offline experience.

### Installation

After cloning or downloading this project, you will need a local server to run
it. The simplest method is using Python's simple HTTP server.
1. Install Python 2.x or Python 3.x from the [Python website](https://www.python.org/downloads/)
2. In your terminal or command line, navigate to the directory containing this project
3. If you installed Python 2, type `python -m SimpleHTTPServer 9100` or, if you
installed Python 3, type `python3 -m http.server 3000`

### Usage

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
