Amazon Wishlist API / Scraper
=

[![Build Status](https://travis-ci.org/ScalaWilliam/amazon-wishlist-api.svg?branch=master)](https://travis-ci.org/ScalaWilliam/amazon-wishlist-api)

Demo:
http://demo.scalawilliam.com/amazon-wishlist-api/

Every push to master is deployed continuously and automatically with courtesy of AWS SQS.

Stuff:
* Play 2.5.1
* sbt 0.13.11
* Scala 2.11.8
* spray-client 1.3.3
* React
* JSoup

![Example JSON response](json.png)
![Example AngularJS UI](screenshot.png)
![Source Wishlist example](amazon.png)

This trawler does deal with large Wishlists, ie composed of multiple pages.
