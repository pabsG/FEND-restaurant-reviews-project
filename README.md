# Restaurant Reviews Web Application

## Table of Contents

* [Description](#Description)
* [How To Run](#How-To-Run)
* [Work Summary](#Work-Summary)

## Description

For this project, I was given starting code for a restaurant reviews website. The requirements for the project was to make it responsive using CSS, to improve accessibility features and to provide functionality to make sure the app works offline.

In the end, I used HTML, CSS and JavaScript to achieve these functionalities. Starting with responsiveness, this repo includes a responsive.css file for different viewport sizes. The original style.css was modified and optimized for mobile screens.

Accessibility was achieved by a combination of old-fashioned html, as well as some modifications to the objects in the provided js files to make sure the html elements created included tab index and aria labels.

Finally, offline functionality was achieved by creating a simple service worker at the root level that caches all the files in this repo to local storage.

## How To Run

To run the website, visit [this website.](https://pabsg.github.io/FEND-restaurant-reviews-project/) Any modern web browser should be able to run this app, however I would recommend [Google Chrome.](https://www.google.com/chrome/)

Alternatively, you could download this repo and serve the site files through a local hosting solution. I used Python 2.x while working on this project, but any other localhost:your-port-number-here solution should work.
