# Udacity Project 6: FeedReader Testing
Part of the Front-End Web Developer nanodegree from Udacity. The project utilizes concepts learned from the [JavaScript Testing](https://www.udacity.com/course/viewer#!/c-ud549-nd) course.

##Usage

Clone the repository locally and run `index.html`.
```
git clone git@github.com:d3moid/frontend-feedreader-testing.git
```

##Purpose
In this project we are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where we come in.

## Tests

1. Loop through each feed in the allFeeds object and ensure it has a URL defined and that the URL is not empty.
2. Loop through each feed in the allFeeds object and ensure it has a name defined and that the name is not empty.
3. Ensure the menu element is hidden by default.
4. Menu changes visibility when the menu icon is clicked.
5. Ensure when the loadFeed function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
6. Ensure that when a new feed is loaded by the loadFeed function the content actually changes.
