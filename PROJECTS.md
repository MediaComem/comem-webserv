# Projects

These are a few suggestions of projects to develop for the course.

* [Crowdfind](#crowfind)
* [Travel log](#travel-log)
* [Trip advisor](#trip-advisor)
* [Other](#other)



## Crowdfind

Ask the community to find where you can buy something.

<img src='images/domain-model-crowdfind.png' />

* **User**
  * Username and/or email
  * Password
  * Registration date
* **Item**
  * Description
  * Optional picture
  * Creation date
* **Sighting**
  * Description
  * Geolocation
  * Picture
  * Optional price
  * Creation date

Example of aggregated data:

* The lowest/average/maximum price found for an item.
* The number of sightings for an item.
* The number of items created by a user.



## Travel log

Take pictures of places along your trip.

<img src='images/domain-model-travel-log.png' />

* **User**
  * Username and/or email
  * Password
  * Registration date
* **Trip**
  * Description
  * Creation date
* **Place**
  * Description
  * Geolocation
  * Picture
  * Creation date

Examples of aggregated data:

* The number of trips made by a user.
* The number of places in a trip.



## Trip advisor

Find and rate places to eat, sleep or visit.

<img src='images/domain-model-trip-advisor.png' />

* **User**
  * Username and/or email
  * Password
  * Registration date
* **Place**
  * Description
  * Geolocation
  * Picture
  * Creation date
* **Comment**
  * Rating
  * Description
  * Optional picture
  * Creation date

Examples of aggregated data:

* The lowest/average/maximum rating of a place.
* The number of comments for a place.
* The number of comments made by a user.



## Other

Other ideas can be accepted as long as they meet the [evaluation criteria](README.md#evaluation).
You may find inspiration there:

* [Idea Machine](http://www.ideamachine.io/#view-ideas-top)
* [Ideas Watch](https://www.ideaswatch.com/startup-ideas/app)
