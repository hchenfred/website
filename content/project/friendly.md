+++
# Date this page was created.
date = "2017-06-03"

# Project title.
title = "Friend.ly"

# Project summary to display on homepage.
summary = "An iOS app which allows user to create events and invite friends to events. Friends could propose new activities for an event and vote on activities. It is built with React Native, Redux, Express and MySQL"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "friendly1.jpeg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["demo"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = "Friend.ly"

+++

Friend.ly is an iOS app which allows user to create events and invite friends to events. Friends could propose new activities for an event and vote on activities.

## Tech Stack
* React Native
* Redux
* [React Navigation](https://reactnavigation.org/) 
* Facebook iOS SDK
* Webpack
* Express
* MySQL

## UI
{{< figure src="/img/friendly1.jpeg" title="User Interface 1" >}}
{{< figure src="/img/friendly2.jpeg" title="User Interface 2" >}}

## Technical Contribution
* Constructed front-end with React Native to render forms for user input and to display data from states 
* Implemented Redux  with actions and reducers for centralized state management
* Built infrastructure for user authentication with Facebook iOS SDK to retrieve and store user profile data
* Designed React Navigation for ease of use when switching views between React components 
* Built request handlers at back-end with Express.js to populate relational tables in MySQL with Promises
* Constructed tests with Jest for React Native components and Redux actions/reducers at front-end and with Mocha/Chai for request handlers and integration between Express.js and database at back-end
