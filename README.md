Restaurant Reviews App
===============================

# Table of Contents

* [Project Overview](#project-overview)
* [How To Run the Application](#run-the-application)
* [Development Strategy](#development-strategy)



## Project Overview

For the Restaurant Reviews project, a static webpage is converted to a mobile-ready web application. In Stage One, a static design that lacks accessibility is provided and converted the design to be responsive on different sized displays and made it accessible for screen reader use. Converted this to a Progressive Web Application by caching some assets for offline use.

## How To Run the Application

* Download as .zip file or clone this project:

* In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

* In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8002` (or some other port, if port 8002 is already in use.) For Python 3.x, you can use `python3 -m http.server 8002`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

* With your server running, visit the site: `http://localhost:8002`.

## Development Strategy

* Got a MapBox API key.
* Got the map on the screen.
* Converted the provided site to use a responsive design.
* Implemented accessibility features in the site HTML.
* Added a ServiceWorker script.
