#Udacity Fend-P5-feed-reader
======

This is my take on a project for the Udacity frontend nanodegree course introducing testing Javascript code using the Jasmine framework.
You are given a blog site which fetches feeds from an API and have to write various tests for it.

##Instructions
------

In order to run this application, clone or download the files of this project and open `index.html` in your browser(the tests will be run automatically with feedback shown below the page content).

##Test specifications
------

To look at all the tests, please navigate to `jasmine/spec/` and open `feedreader.js` in your editor.
All in all there are 4 different test suites:

1. **RSS Feeds**

...checks if the allFeeds variable is defined and not empty

...checks if the objects stored within allFeeds have a URL

...checks if the objects stored within allFeeds have a name

2. **The menu**

...checks if the menu bar is initially hidden on page start-up

...checks if the menu bar class is toggled when the burger icon is clicked

3. **Initial Entries**

...checks if there is at least one entry within the feed container

4. **New Feed Selection**
...checks if the content changes when another category is chosen(a different index of the allFeeds-array is called)