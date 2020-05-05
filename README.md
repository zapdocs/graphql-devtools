[![Build Status](https://travis-ci.org/s12v/graphql-devtools.svg?branch=master)](https://travis-ci.org/s12v/graphql-devtools)

# GraphQL Chrome DevTools extension

This extension adds a new tab to Chrome developer tools:

![GraphQL developer tools](https://user-images.githubusercontent.com/1462574/32994379-d636fb8e-cd66-11e7-8b1d-516666579173.png)

## Getting Started

Installation

1. In Chrome browser, go to chrome://extensions page and switch on developer mode. This enables the ability to locally install a Chrome extension.
2. Install npm packages as you normally do with any node project with `yarn`. This installs the project specific npm packages
3. Build this app as you normally build a react app with `yarn build`. This generates the app and place the files inside [PROJECT_HOME]/build.
3. Now click on the `LOAD UNPACKED` and browse to `[PROJECT_HOME]/build` ,This will install the React app as a Chrome extension.

Assumes `yarn` is installed, it can be installed with `npm install -g yarn` 


How to try

Navigate to https://www.graphqlhub.com/playground/github, and inspect the page.