## Website Performance Optimization portfolio project

This project is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

check [this link](http://kaitohh.com/frontend-nanodegree-mobile-portfolio/) to see the pages

### Changes

#### index.html
- async some javascript files
- inline css files and remove from blocking
- optimize the size of some images
- minimize external javascript and css files

#### views/js/main.js
- reduce query times
- eliminate unnecessary redundant code
- reduce the amount of background items

### How to run
There are few methods to run this website.
- Simply open index.html to see webpage
- create a HTTP server on the root folder by using Python, apache or other similar web server and then open http://localhost:[your_port]
