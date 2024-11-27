# bookmarklets

A bookmarklet is a JavaScript snippet that can be run within a web
browser and that typically performs an action related to the currently
loaded web page.

This repo is a starting point for developing bookmarklets using vanilla JavaScript.

## Features

- Compiles JS and CSS files into a single HTML page with a bookmarklet link.
- optionally encode the bookmarklet using Base64 or URL encoding (necessary if they contain special characters) (not implemented)

Note: In very simple cases, you may want to inline the JS and CSS directly into the bookmarklet. Practically you're limited to the browser URL length limit (roughly around 32,000 characters in Chrome, 65,000 in Firefox, and 8,192 in Safari).

## Getting started

1. clone this repo
2. hack away :)

## Deploying

Once you're done building your bookmarklet, you'll need to:

1. host main.js and style.css
2. update the link in index.html (that starts with `javascript:` to point to your hosted files)