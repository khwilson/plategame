This is a simple little game to teach the tradeoffs of binary search.
The idea is that you're testing on which floor a particular plate
will break. But you only have a fixed number of plates! How can you
find the floor on which the plate actually breaks?

Currently a bunch of hacks:
* Restart by refreshing
* Change number of floors and number of plates by query argument, e.g.,
  index.html?floors=30&plates=3
* Janky instructions

Anyway, it requires calling out to a CDN for paper.js. Also, requires
a reasonably modern browser.

Made for my AP CS class in < 2 hours by a non-JS person. So forgive my
style. Also, feel free to gank and use for yourself.
