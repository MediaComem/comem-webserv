# COMEM+ Web Services course

The goal of this course is to teach the generic concept of **web service**, focusing on **REST**ful APIs as one way to expose such a service.
You will:

* Learn the **core principles** of the REST architectural style
* Learn how to **implement** a RESTful API in JavaScript
* Learn how to **manage** your source code on a collaborative platform
* Learn how to **deploy** your RESTful API on a cloud application platform

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

* [Introduction](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/webserv-course?home=MediaComem%2Fcomem-webserv%23readme)

* Tooling
  * [Command line](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/cli?home=MediaComem%2Fcomem-webserv%23readme)
  * [Version control with Git](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/git?home=MediaComem%2Fcomem-webserv%23readme)
  * [Git branching](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/git-branching?home=MediaComem%2Fcomem-webserv%23readme)
  * [Collaborating with Git](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/git-collaborating?home=MediaComem%2Fcomem-webserv%23readme)

* Basics
  * [JavaScript](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/js?home=MediaComem%2Fcomem-webserv%23readme)
  * [Node.js](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/node?home=MediaComem%2Fcomem-webserv%23readme) JavaScript runtime
  * [npm](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/npm?home=MediaComem%2Fcomem-webserv%23readme) Node.js package manager
  * [RESTful APIs](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/rest?home=MediaComem%2Fcomem-webserv%23readme)

* Creating a web service
  * [Express](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/express?home=MediaComem%2Fcomem-webserv%23readme) web framework
  * [MongoDB](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/mongodb?home=MediaComem%2Fcomem-webserv%23readme) document-oriented database
  * [Mongoose](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/mongoose?home=MediaComem%2Fcomem-webserv%23readme) Object-Document Mapper

* Deploying your web service
  * [Heroku](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/heroku?home=MediaComem%2Fcomem-webserv%23readme) cloud application platform

* Enriching your web service
  * [RESTful API conventions](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/rest-conventions?home=MediaComem%2Fcomem-webserv%23readme)
  * [Express best practices](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/express-best-practices?home=MediaComem%2Fcomem-webserv%23readme)
  * [Utilizing Mongoose](https://mediacomem.github.io/comem-webdev-docs/2017/subjects/express-mongoose?home=MediaComem%2Fcomem-webserv%23readme) in Express (filtering, pagination, aggregation)
  * RESTful API documentation



## What you will need

* [Google Chrome][chrome] (recommended, any browser with developer tools will do)
* [Git][git-downloads]
* [Postman][postman] (recommended, any tool that makes raw HTTP requests will do)



## Useful links

* [Architecture & source code management diagrams][diagrams]
* [Demonstration REST API implemented with Express][demo-api] ([documentation][demo-api-doc])



## Evaluation

**Web Service**

Your REST API must be based on (at least) [this domain model](DOMAIN-MODEL.md) and provide (at least) the following operations:

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
* Your Express routes must handle asynchronous operation errors
* Your API must validate user input (e.g. using Mongoose validations)
* *Bonus*: your API must validate the existence of linked resources (e.g. when creating an issue linked to a user)

**Bonuses**

Items with the *Bonus* mention are not required to obtain the maximum grade,
but will increase your grade if there are other issues in your project.

### Delivery

Send an e-mail **no later than March 13th 2017** to Simon Oulevay and Jean-Pierre Hess with:

* The list of group members
* The link to your source code repository on GitHub
* The to your deployed REST API on Heroku



[chrome]: https://www.google.com/chrome/
[comem]: http://www.heig-vd.ch/comem
[comem-webdev]: https://github.com/MediaComem/comem-webdev
[demo-api]: https://github.com/MediaComem/comem-webdev-express-rest-demo
[demo-api-doc]: https://mediacomem.github.io/comem-webdev-express-rest-demo/
[diagrams]: diagrams.pdf
[git-downloads]: https://git-scm.com/downloads
[heig]: http://www.heig-vd.ch
[postman]: https://www.getpostman.com
