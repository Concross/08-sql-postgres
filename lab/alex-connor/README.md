# Lab 08

**Author**: Alex
**Version**: 2.1.0 

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it’s an assignment for a Code Fellows 301 class. (i.e. What’s your problem domain?) -->
We are building a blog that can add articles that can be filtered by author and category.  It also has a navbar which uses SPA design. It requests articles from a database and renders new changes as they are made.

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->

1. Fork and clone the repo
2. Initialize npm in root folder
  'npm init'
  'npm install'
  'npm install pg --save'
3. Run 'nodemon server.js'
4. Make sure postgres is running with user and password to add to the conString in server.js

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you’re using, and any other relevant design information. -->

Languages: JS, CSS/HTML
Platform: Node.js
Frameworks: Express.js
Database: Postgresql
Templating: Handlebars.js
Libraries: jQuery, Marked.js, Highlight.js
Strategies: AJAX, SMACSS

## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here’s an examples: -->

08-02-18 8:00am - Initial commit with copied folder from starter
08-02-18 8:10am - Updated dependencies and completed review of existing code base
08-02-18 9:10am - Added modules, created conString, created connection for client to database
08-02-18 9:45am - Added query strings, responded to comments for CRUD reviews
08-02-18 10:15am - Added more query strings, responded to remaining comments for CRUD reviews
08-02-18 11:05am - Added README.md, tested queries, fixed bugs in queries.


## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. --> Connor Crossley and Alex Hanson