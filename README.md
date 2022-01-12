# The Optional Express

## Quick Setup
1. Fork and clone this repo.
2. cd into the directory `cd the-optional-express`
3. Create your directories/files (please don't forget to add .gitignore).
4. Open this directory in VS Code with: `code .`

## Basic Instructions
### Based on what we've covered with express and node so far, build your own version of [sell-it-up](https://peat-sparrow-54f.notion.site/MVC-0629e27eb8d947c18e25fd844069710e). You could use [pug](https://pugjs.org/api/getting-started.html) or [ejs](https://www.npmjs.com/package/ejs) for this assignment.

* In your server.js file, start with the basic building blocks of express. Use node `server.js` or `nodemon server.js` to verify that it works.
* Create your own temporary database (examples could be products, pets, games, etc.). The database should have a title, image, and basic info.

#### Using routes and controllers, an user should be able to view:
* a styled page (with images) to view everything from your db. `localhost:4000/name-of-db-here`
* a styled page to see an individual index. `localhost:4000/name-of-db-here/:index`
* a very sad 404 page if they enter a bad url request.
