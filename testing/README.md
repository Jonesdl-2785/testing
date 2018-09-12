# FEND Feedreader Testing Project
## Description
This project is a basic introduction to writing test scripts and the industry standard practice of "test-driven development".  

## Project Overview
The project consists of a completed RSS Feed web app (which loads feeds from various websites) to be tested and Jasmine 2.1.2 http://jasmine.github.io/

## Project Goal
The goal of this project is to write proper, well-crafted test scripts, use the Jasmine testing framework to test and, successfully, pass each test requirement.

## Project Core Requirements/SPECs

1. Edit the `allFeeds` variable in **./js/app.js** to make the provided test fail and see how Jasmine visualizes this failure in your application.
2. Return the `allFeeds` variable to a passing state.
3. Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
4. Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
5. Write a new test suite named `"The menu"`.
6. Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
7. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
8. Write a test suite named `"Initial Entries"`.
9. Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
10. Write a test suite named `"New Feed Selection"`.
11. Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
12. No test should be dependent on the results of another.
13. Callbacks should be used to ensure that feeds are loaded before they are tested.
14. Implement error handling for undefined variables and out-of-bound array access.
15. When complete - all of your tests should pass.

## Setup
Retrieved project assets from github (download or clone to you local machine) (see link below).
Using the text editor of your choice, launch project and review.
Open the index.html file in the browser of your choice.

## Testing
In the browser, you will see the web app, and the Jasmine Dashboard at the bottom of the screen. Scroll to move to
the top of the window.
In the editor, navigate to the feedreader.js file, which contains the testing specs and TODOs.

## Expected Results
7 specs, 0 failures
Jasmine__TopLevel__Suite
RSS Feeds
are defined
all urls are defined
name defined
The menu
menu is hidden by default
menu toggles on and off when clicked
Initial Entries
a single .entry element is in the .feed container after work completes
New Feed Selection
new feed is loaded by the loadFeed function, the content changes               

#### Udacity Resources
#### [course](https://www.udacity.com/course/ud549)
#### Download the [required project assets](http://github.com/udacity/frontend-nanodegree-feedreader)
