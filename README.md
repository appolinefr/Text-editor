# Text-editor

## Table of content

- [Description of Project](#description-of-project)
- [Project Requirements](#project-requirements)
- [What I have learned](#what-i-have-learned)
- [Challenges](#challenges)
- [Link to deployed application](#link-to-deployed-application)

## Description of Project

This challenge was to build a text editor that runs in the browser. The app is a single-page application that meets the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.

## Project Requirements

Here are the main requirements of the project:

- When I open the text editor then I find that IndexedDB has immediately created a database storage
- When I enter content and subsequently click off of the DOM window then I find that the content in the text editor has been saved with IndexedDB
- When I reopen the text editor after closing it then I find that the content in the text editor has been retrieved from our IndexedDB
- When I click on the Install button then I download my web application as an icon on my desktop
- When I load my web application then I should have a registered service worker using workbox
- When I register a service worker then I should have my static assets pre cached upon loading along with subsequent pages and static assets
- When I deploy to Heroku then I should have proper build scripts for a webpack application

## What I have learned 

 Converting an existing application into a progressive web application was challenging but it was a great way to put in practice eveyrything I have learned about PWA. I am now able to implement service workers and different caching strategies as well as IndexedDB inside of a JavaScript application. 

## Challenges

Implementing the caching strategy was initally a challenge but Workbox and its set of libraries as well as detailed documentation allowed me to eventually implement it. This will be a great skill to have in future projects.


### Link to deployed application

[Link to deployed application](https://vast-shelf-62789.herokuapp.com/)
