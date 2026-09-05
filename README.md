# NIGHTSHIFT course website

A static four-page ethical hacking course website built with HTML, CSS, Bootstrap and vanilla JavaScript.

## Pages

- `index.html` - animated long-form landing page
- `courses.html` - filterable course catalog
- `learn.html` - payment desk and video lesson access
- `about.html` - course principles and responsible-use boundary

## Run

Open `index.html` directly in a browser, or serve this folder with any static server.

The payment flow is a front-end demo: entering a transaction ID stores an unlock flag in `localStorage`. For production, connect the form to a verified payment provider and a server-side entitlement check. Replace the sample video URL in `assets/js/app.js` with your own hosted lesson files.
