Raphaël + Flot = Raphlot
========================

An port of [Flot](http://code.google.com/p/flot/) to use the [Raphaël](http://raphaeljs.com/) APIs.

Advantages of this approach:

* SVG is a vector format, which is much better suited to drawing graphs.
* No need for excanvas
* Looks better at arbitrary zoom levels (important for multitouch devices)
* IE9 will support hardware-accelerated SVG

Disadvantages:

* It's currently a little slower than Canvas
* No support on Android

This code is currently being served to users of [timetric.com](http://timetric.com) if their browser supports SVG, otherwise they get Flash. (This is for performance reasons — Raphlot works well on IE because of Raphaël's VML support.)