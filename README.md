# ui-challenge-01

**Author**: Maxwell Rediker
**Version**: 1.0.1 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 301 class. (i.e. What's your problem domain?) -->
This is  aassignment to demonstrate skills in building a responsive web layout with a mobile-first methodology approach

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
1. in HTML set up each "box" being a class named div and have the correct container div around it. in other words have the 4 divs inside a container for the 4-up section and 2 divs in a container for the 2-up section. dont forget the designated letters that are inside the div boxes.
2. in CSS set up the three files base, layout, and modules and link them in the HTML page
3. in CSS set widths, heights, borders, backgrounds of the divs and containers / set the appropriate media query at the desired breakpoint (remember mobile first)
4. in CSS set the floats on the divs ( and any clears that are needed)
5. position the letters vertically and horizontally within their respective divs

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->
HTML and CSS

Header = @MOBILE and @DESKTOP this is the entire designated width
Feature = @MOBILE this is the entire designated width @DESKTOP the dimensions are changed at it is floated left to act as an aside element
2-up = @MOBILE each element is floated left so they stack / @DESKTOP 
4-up = @MOBILE each set two of these divs are floated left / @DESKTOP only the parent container is floated left
footer = @MOBILE and @DESKTOP this is the entire designated width


## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples:-->

Merge pull request #1 from GitHubMaxwell/max-branch1
GitHubMaxwell committed 10:45am

made code DRY
GitHubMaxwell committed 10:45am

finished all ui challenge requirements
GitHubMaxwell committed 10:30am

Initial commit
GitHubMaxwell committed 9am


## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. -->
Maxwell Rediker
css-tricks.com to figure out vertical and horizontal positioning