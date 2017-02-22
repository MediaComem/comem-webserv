# COMEM+ Web Services course

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Plan](#plan)
- [What you will need](#what-you-will-need)
- [Useful links](#useful-links)
- [Evaluation](#evaluation)
  - [Delivery](#delivery)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->



## Plan

* [Introduction](https://mediacomem.github.io/comem-webdev-docs/subjects/webserv-course?home=MediaComem%2Fcomem-webserv%23readme)

* Tooling
  * [Command line](https://mediacomem.github.io/comem-webdev-docs/subjects/cli?home=MediaComem%2Fcomem-webserv%23readme)
  * [Version control with Git](https://mediacomem.github.io/comem-webdev-docs/subjects/git?home=MediaComem%2Fcomem-webserv%23readme)
  * [Git branching](https://mediacomem.github.io/comem-webdev-docs/subjects/git-branching?home=MediaComem%2Fcomem-webserv%23readme)
  * [Collaborating with Git](https://mediacomem.github.io/comem-webdev-docs/subjects/git-collaborating?home=MediaComem%2Fcomem-webserv%23readme)

* Basics
  * [JavaScript](https://mediacomem.github.io/comem-webdev-docs/subjects/js?home=MediaComem%2Fcomem-webserv%23readme)
  * [Node.js](https://mediacomem.github.io/comem-webdev-docs/subjects/node?home=MediaComem%2Fcomem-webserv%23readme) JavaScript runtime
  * [npm](https://mediacomem.github.io/comem-webdev-docs/subjects/npm?home=MediaComem%2Fcomem-webserv%23readme) Node.js package manager
  * [REST APIs](https://mediacomem.github.io/comem-webdev-docs/subjects/rest?home=MediaComem%2Fcomem-webserv%23readme)

* Creating and deploying a web service
  * [Express](https://mediacomem.github.io/comem-webdev-docs/subjects/express?home=MediaComem%2Fcomem-webserv%23readme) web framework
  * [Heroku](https://mediacomem.github.io/comem-webdev-docs/subjects/heroku?home=MediaComem%2Fcomem-webserv%23readme) cloud application platform

* Plugging in the database
  * [MongoDB](https://mediacomem.github.io/comem-webdev-docs/subjects/mongodb?home=MediaComem%2Fcomem-webserv%23readme) document-oriented database
  * [Mongoose](https://mediacomem.github.io/comem-webdev-docs/subjects/mongoose?home=MediaComem%2Fcomem-webserv%23readme) Object-Document Mapper

* Enriching the web service
  * REST API conventions
  * REST API documentation
  * JavaScript closures
  * Filtering with Express & Mongoose
  * Pagination with Express & Mongoose
  * MongoDB aggregations



## What you will need

* [Google Chrome][chrome] (recommended, any browser with developer tools will do)
* [Git][git-downloads]
* [Postman][postman] (recommended, any tool that makes raw HTTP requests will do)



## Useful links

* [Architecture & source code management diagrams][diagrams]
* [Demonstration REST API implemented with Express][demo-api]



## Evaluation

**Web Service**

Your REST API must provide (at least) the following operations:

* Create a user
* Retrieve a user
  * *Bonus:* the response indicates how many issues the user has created
* Update a user (fully or partially)
* Create an issue
  * The issue must belong to one user
* Retrieve an issue
* Retrieve the list of issues
  * *Bonus:* the list is paginated
  * *Bonus:* there is at least 1 filter
* Update an issue (fully or partially)
* Delete an issue

**Infrastructure**

* The source code of your REST API must be in a repository on GitHub
* Your REST API must be deployed on Heroku

**Documentation**

* Your REST API must be documented

**Quality of the implementation**

* You must follow REST best practices
* Your Express routes must handle errors

Items with the *Bonus* mention are not required to obtain the maximum grade,
but will increase your grade if there are other issues in your project.

### Delivery

Send an e-mail **no later than March 13th 2017** to Simon Oulevay and Jean-Pierre Hess with:

* The list of group members
* The link to your source code repository on GitHub
* The to your deployed REST API on Heroku



[chrome]: https://www.google.com/chrome/
[demo-api]: https://github.com/MediaComem/comem-webdev-express-rest-demo
[diagrams]: diagrams.pdf
[git-downloads]: https://git-scm.com/downloads
[postman]: https://www.getpostman.com
