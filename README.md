# Project Overview

In this project I was given a web-based application that reads RSS feeds.
The original developer of this application clearly saw the value in testing,
they've already included [Jasmine](http://jasmine.github.io/)
and even started writing their first test suite!
But left with an application with an incomplete test suite.
I have finished the expected tests, using Jasmine 2.1.2.


## To Run The Program

1. Clone/Download the project files from Github https://github.com/beloved/feed-reader-testing
2. Unzip files if necessary.
3. Open index.html in your favorite browser
4. At the bottom of the page you will see the tests completed by using Standalone Jasmine 2.1.2
### The tests include:

- test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
- test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
- test that ensures the menu element is hidden by default.
- test that ensures the menu changes visibility when the menu icon is clicked.
- test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
- test that ensures when a new feed is loaded by the `loadFeed` function that the content changes.

