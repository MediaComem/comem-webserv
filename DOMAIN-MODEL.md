# Citizen Engagement Domain Model

This is a **minimal domain model** for the Citizen Engagement project in the COMEM+ Web Services course.
This is not enough to create a complete Citizen Engagement API, but is what is asked for this course.
A full-featured API will be provided to you for the next course (Mobile Applications).

## Users

Users are citizens (or city managers) who can use the Citizen engagement application to report and solve issues.

They have (at least) the following properties:

* `firstName` - String, 2-20 characters
* `lastName` - String, 2-20 characters
* `role` - String, "citizen" or "manager"
* `createdAt` - Date, the date at which the user was registered

And the following constraints:

* Two users **must not** have the same first and last name

## Issues

Issues are problems in the city such as broken street lamps, graffiti, etc.

They have (at least) the following properties:

* `status` - String, "new", "inProgress", "canceled" or "completed", the status of the issue:
  * Defaults to "new" when the issue is created
  * Change from "new" to "inProgress" to indicate that a city employee is working on the issue
  * Change from "new" or "inProgress" to "canceled" to indicate that a city employee has determined this is not a real issue
  * Change from "inProgress" to "completed" to indicate that the issue has been resolved
  * Other status transitions should be forbidden by the API
* `description` - (Optional) String, 1000 characters max, a detailed description of the issue
* `imageUrl` - (Optional) String, 500 characters max, a URL to a picture of the issue
* `latitude` - Number, the latitude (part of the coordinates indicating where the issue is)
* `longitude` - Number, the longitude (part of the coordinates indicating where the issue is)
* `tags` - Array of Strings, user-defined tags to describe the issue (e.g. "accident", "broken")
* `user` - User, the user who reported the issue
* `createdAt` - Date, the date at which the issue was reported
* `updatedAt` - Date, the date at which the issue was last modified
