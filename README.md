simplerating
============

A simple directive to manage rating with nice star :)

Usage
=====

Just add it to your app to have a nice rate component

Dependency
==========

[Bootstrap 3](http://getbootstrap.com/) for the star glyphicon

How it works
============

An example is available on "example" directory

```html
<!-- Include SimpleRating -->
<script src="simplerating.js"></script>
<!-- ... -->
<body>
<!-- ... -->
<div simple-rating rating="ratingValue" rating-max="max" read-only="readonly"></div>
<!-- ... -->
```

Parameters :
* rating : the rate value
* rating-max : the number max of star
* read-only : true to avoid modification, otherwise false to allow

