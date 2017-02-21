# COMEM+ Web Services course



## Tools

* [Google Chrome][chrome] (recommended, any browser with developer tools will do)
* [Postman][postman] (recommended, any tool that makes raw HTTP requests will do)



## Plan

* Citizen Engagement project
* Architecture

* Tooling
  * [Command line](https://mediacomem.github.io/comem-webdev-docs/subjects/cli?home=MediaComem%2Fcomem-webserv%23readme)
  * [Version control with Git](https://mediacomem.github.io/comem-webdev-docs/subjects/git?home=MediaComem%2Fcomem-webserv%23readme)
  * [Git branching](https://mediacomem.github.io/comem-webdev-docs/subjects/git-branching?home=MediaComem%2Fcomem-webserv%23readme)
  * [Collaborating with Git](https://mediacomem.github.io/comem-webdev-docs/subjects/git-collaborating?home=MediaComem%2Fcomem-webserv%23readme)

* Basics
  * [JavaScript](https://mediacomem.github.io/comem-webdev-docs/subjects/js?home=MediaComem%2Fcomem-webserv%23readme)
  * [Node.js](https://mediacomem.github.io/comem-webdev-docs/subjects/node?home=MediaComem%2Fcomem-webserv%23readme) server-side JavaScript runtime
  * [npm](https://mediacomem.github.io/comem-webdev-docs/subjects/npm?home=MediaComem%2Fcomem-webserv%23readme) Node.js package manager
  * [REST APIs](https://mediacomem.github.io/comem-webdev-docs/subjects/rest?home=MediaComem%2Fcomem-webserv%23readme)

* Creating and deploying a web service
  * [Express](https://mediacomem.github.io/comem-webdev-docs/subjects/express?home=MediaComem%2Fcomem-webserv%23readme) web framework
  * [Heroku](https://mediacomem.github.io/comem-webdev-docs/subjects/heroku?home=MediaComem%2Fcomem-webserv%23readme) cloud application platform

* Plugging in the database
  * [MongoDB](https://mediacomem.github.io/comem-webdev-docs/subjects/mongodb?home=MediaComem%2Fcomem-webserv%23readme) database
  * [Mongoose](https://mediacomem.github.io/comem-webdev-docs/subjects/mongoose?home=MediaComem%2Fcomem-webserv%23readme) Object-Document Mapper

* Going further
  * JavaScript closures
  * JavaScript asynchronous code
  * [REST API conventions](https://mediacomem.github.io/comem-webdev-docs/subjects/rest-conventions?home=MediaComem%2Fcomem-webserv%23readme)
  * REST API documentation
  * Express middleware
  * Filtering with Express & Mongoose
  * Pagination with Express & Mongoose
  * Mongoose population
  * MongoDB aggregations
  * MongoDB geospatial queries



## Evaluation

**Web Service**

Your REST API must provide (at least) the following operations:

* Create a user
* Retrieve a user
  * The response should indicate how many issues the user has created
* Update a user
* Create an issue
  * The issue must belong to one user
* Retrieve an issue
* Retrieve a list of issues
  * The list should be paginated
  * There should be at least 1 filter
* Update an issue
* Delete an issue

**Delivery**

* The source code of your REST API must be in a repository on GitHub
* Your REST API must be deployed on Heroku

**Documentation**

* Your REST API must be documented

**Quality of the implementation**

* You should follow REST best practices
* Your asynchronous code should be correct
* Your Express routes should handle errors

### Delivery

* Send an e-mail to Simon Oulevay and Jean-Pierre Hess with:
  * The list of group members
  * The link to your source code repository on GitHub
  * The link to your deployed REST API on Heroku



## Old plan (from previous course)

* JavaScript
  * Basics

* Node.js
  * Asynchronicity
  * npm

* Express.js
  * Middleware
  * Routing
  * Postman

* PaaS (Heroku)

* MongoDB
  * Embedded vs collection

* Mongoose

* REST principles:
  * REST
  * CRUD
  * URL structure
  * Linked resources
  * Resources & actions
  * Pagination
  * Sorting **more examples**
  * Filtering
  * Authentication

* MongoDB, Mongoose & Express.js examples
  * Parsing request data
  * Avoiding repetition with middleware
  * Filtering
  * Mongoose references & population
  * Pagination
  * Aggregations

* Geospatial queries

* JavaScript principles:
  * Scopes
  * Prototypes
  * Classes
  * Closures
  * Asynchronous code

* REST API documentation:
  * RAML
  * ApiDoc
  * Markdown



[chrome]: https://www.google.com/chrome/
[postman]: https://www.getpostman.com
