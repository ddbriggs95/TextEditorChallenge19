# PWA-Text-Editor


## Description

This is a progressive web application that can function in a browser operating both online and offline. Additionally, the app can be used in a freestanding context and still operate correctly (by use of an integrated service worker and Cache APIs). The goal was to showcase a platform for users to be able to take notes or write code snippets regardless of having an active internet connection.

## Acceptance Criteria

GIVEN a text editor web application
- WHEN I open my application in my editor
- THEN I should see a client server folder structure
- WHEN I run 'npm run start' from root directory
- THEN I find that my application should start up the backend and serve the client
- WHEN I run the text editor application from my terminal
- THEN I find that my JavaScript files have been bundled using webpack
- WHEN I run my webpack plugins
- THEN I find that I have generated HTML file, service worker, and manifest file
- WHEN I use next-gen JavaScript in my application
- THEN I find that the txt editor still functions in the browser withou errors
- WHEN I open the text editor
- THEN I find that IndexedDB has immediately created a database storage
- WHEN I enter content and subsequently click off of the DOM window
- THEN I find that the content in the text editor has been saved with IndexedDB
- WHEN I reopen the text editor after closing it
- THEN I find that the content in the text editor has been retrieved from our IndexedDB
- WHEN I click on the Install button
- THEN I download my web application as an icon on my desktop
- WHEN I load my web application
- THEN I should have a registered service worker using workbox
- WHEN I register a service worker
- THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
- WHEN I deploy to Heroku
- THEN I should have proper build scripts for a webpack application



## Deployment

Deployed App on Heroku: https://dowbriggspwachallenge19.herokuapp.com/

GitHub Repo: https://github.com/ddbriggs95/pwa-text-editor

