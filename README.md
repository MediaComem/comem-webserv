# COMEM+ Web Services course

The goal of this course is to teach the generic concept of **web service**,
focusing on **REST**ful APIs as one way to expose such a service.
You will:

* Learn the **core principles** of the REST architectural style.
* Learn how to **implement** a RESTful API in JavaScript.
* Learn how to **manage** your source code on a collaborative platform.
* Learn how to **deploy** your RESTful API on a cloud application platform.

This course is a [COMEM+][comem] [web development course][comem-webdev] taught at [HEIG-VD][heig].

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Plan](#plan)
- [What you will need](#what-you-will-need)
- [Useful links](#useful-links)
- [Evaluation](#evaluation)
  - [Delivery](#delivery)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->



## Plan

* [Introduction](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/webserv-course?home=MediaComem%2Fcomem-webserv%23readme)

* Tooling
  * [Command line](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/cli?home=MediaComem%2Fcomem-webserv%23readme)
  * [Version control with Git](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/git?home=MediaComem%2Fcomem-webserv%23readme)
  * [Git branching](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/git-branching?home=MediaComem%2Fcomem-webserv%23readme)
  * [Collaborating with Git](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/git-collaborating?home=MediaComem%2Fcomem-webserv%23readme)

* Basics
  * [JavaScript](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/js?home=MediaComem%2Fcomem-webserv%23readme)
  * [Node.js](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/node?home=MediaComem%2Fcomem-webserv%23readme) JavaScript runtime
  * [npm](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/npm?home=MediaComem%2Fcomem-webserv%23readme) Node.js package manager
  * [RESTful APIs](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/rest?home=MediaComem%2Fcomem-webserv%23readme)

* Creating a web service
  * [Express](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/express?home=MediaComem%2Fcomem-webserv%23readme) web framework
  * [MongoDB](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/mongodb?home=MediaComem%2Fcomem-webserv%23readme) document-oriented database
  * [Mongoose](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/mongoose?home=MediaComem%2Fcomem-webserv%23readme) Object-Document Mapper

* Deploying your web service
  * [Heroku](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/heroku?home=MediaComem%2Fcomem-webserv%23readme) cloud application platform

* Enriching your web service
  * [RESTful API conventions](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/rest-conventions?home=MediaComem%2Fcomem-webserv%23readme)
  * [Express best practices](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/express-best-practices?home=MediaComem%2Fcomem-webserv%23readme)
  * [Utilizing Mongoose](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/express-mongoose?home=MediaComem%2Fcomem-webserv%23readme) in Express (filtering, pagination, aggregation)
  * [RESTful API documentation](https://mediacomem.github.io/comem-webdev-docs/2018-2019/subjects/apidoc?home=MediaComem%2Fcomem-webserv%23readme) with apiDoc



## What you will need

* A Unix CLI (Git Bash is included with Git on Windows)
* [Git][git-downloads]
* A free [GitHub][github] account
* [Google Chrome][chrome] (recommended, any browser with developer tools will do)
* [Node.js][node] 6+
* [Postman][postman] (recommended, any tool that makes raw HTTP requests will do)
* [MongoDB][mongodb]
* A free [Heroku][heroku] account
* The [Heroku CLI][heroku-cli]



## Useful links

* [Architecture & source code management diagrams][diagrams]
* [Demonstration REST API implemented with Express][demo-api] ([documentation][demo-api-doc])
* [Command line cheatsheet][cli-cheatsheet]
* [Git cheatsheet][git-cheatsheet]



## Evaluation

**Web Service**

Your REST API must be developed with the Express framework and use a MongoDB database.
It must provide (at least):

* User management
  * New users must be able to register
  * Log in (users must be able to log in)
* 2 other resources
  * Both resources must be linked together
  * At least one of these resources must be linked to users
  * Minimal CRUD operations to manage those resources
* At least one resource must be a paginated list
* At least one resource must be a list with optional filters
* At least one resource must provide aggregated data from other resources
  (e.g. the number of items created by a user)
* Sensitive operations must be protected by requiring valid authentication

**Infrastructure**

* The source code of your REST API must be in a repository on GitHub.
* Your REST API must be deployed on Heroku.

**Documentation**

* Your REST API must be documented.

**Quality of the implementation**

* You must follow REST best practices.
* Your asynchronous code must be correct.
* Your Express routes must handle asynchronous operation errors.
* You must avoid excessive code duplication (e.g. using Express middleware).
* Your API must have basic validations on user input (e.g. using Mongoose validations).
* Your API must validate the existence of linked resources (e.g. when creating an item linked to a user).



### Delivery

Send an e-mail *no later than __<deadline to be determined>__* to Simon Oulevay with:

* The list of group members.
* The link to your source code repository on GitHub.
* The to your deployed REST API on Heroku.



[chrome]: https://www.google.com/chrome/
[cli-cheatsheet]: https://github.com/MediaComem/comem-webdev/blob/master/CLI-CHEATSHEET.md
[comem]: http://www.heig-vd.ch/comem
[comem-webdev]: https://github.com/MediaComem/comem-webdev
[demo-api]: https://github.com/MediaComem/comem-webdev-express-rest-demo
[demo-api-doc]: https://mediacomem.github.io/comem-webdev-express-rest-demo/
[diagrams]: diagrams.pdf
[git-cheatsheet]: https://github.com/MediaComem/comem-webdev/blob/master/GIT-CHEATSHEET.md
[git-downloads]: https://git-scm.com/downloads
[github]: https://github.com
[heroku]: https://www.heroku.com/home
[heroku-cli]: https://devcenter.heroku.com/articles/heroku-cli
[heig]: http://www.heig-vd.ch
[mongodb]: https://www.mongodb.com
[node]: https://nodejs.org/
[postman]: https://www.getpostman.com
