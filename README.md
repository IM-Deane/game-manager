# Project: Building a RESTful API

TODO: Add project image

TODO: Add link to a live demo

**Current Version:** 0.0.7

## Expanded Version Description:

After completing the backend API I've decided to make the app more interesting.
The next version will feature a client side interface that allows users to
manage a small game library.

The app will come populated with 10 games that will be rendered as a list. The
user can add new games to the library as well edit and delete existing titles.

### Stack:

- HTML5
- TAILWIND CSS
- REACT
- MONGO DB
- EXPRESS/NODE

## Previous Version Description:

~~The goal of this project is to practice building a RESTful API.~~

Although i've built one before, I thought it would be good practice to create
another one.

So, I intend to create a small javascript project that utilizes node.js and
express as its backend.

**Note:** Postman was used to test the routing of this application.

If you're new to the backend, Postman is a great little application that enables
developers to make test requests to their server.

To get started with Postman, you can visit their site and download it.

[https://www.postman.com/downloads/](https://www.postman.com/downloads/).

### Why do we need an Postman to make test requests?

Well the address bar of your browser (ie. Google chrome) only allows you to make
GET requests. This is great when you simply need to fetch information **from**
your server.

However, when you want to test other CRUD functionality, you will need to make
other types of requests. This is what's great about the Postman application.

As I said earlier, it allows your to make other types of requests to your
server.

Thanks Postman.

### Development Stack:

- HTML5
- CSS3
- Javascript
- Node.js
- Express.js

## Version History:

**Version 0.0.7:**

Implemented client navigation and super ugly login form.

Currently the form simply navigates to the library when the user clicks the
button.

I may added authentication at a later stage or remove the login feature.

**Version 0.0.6:**

Created client side API routes.

Also fixed a minor bug which was causing a cross origin request error. I had
placed the cors middleware in the wrong section of server/index.js

**Version 0.0.5:**

Implemented new server-side routing that will handle the CRUD functions of the
game library app.

Currently the app's "database" is an array of javascript objects stored in the
controllers folder.

After the client routing/api is ready, I will create a populated mongodb
database.

**Version 0.0.4:**

Created client side boilerplate using creat-react-app and tailwindcss.

**Version 0.0.3:**

Removed the CRUD logic from the routes module and inserted it into a controllers
module.

Separating the logic from the routes makes the app easier to manage in my
opinion.

I believe this is also "best practice" for medium sized to large scale projects.

**Version 0.0.2:**

Created routes that will handle the CRUD requests.

**Version 0.0.1:**

Created an express server as the basic backend of the site.
