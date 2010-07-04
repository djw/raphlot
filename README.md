Raphaël + Flot = Raphlot
========================

An experimental port of [Flot](http://code.google.com/p/flot/) to use the [Raphaël](http://raphaeljs.com/) APIs.

Advantages of this approach:

* SVG is a vector format, which is much better suited to drawing graphs.
* No need for excanvas
* Looks better at arbitrary zoom levels (important for multitouch devices)
* IE9 will support hardware-accelerated SVG

Disadvantages:

* It's currently a little slower than Canvas
* No support on Android until v2.0 (Gingerbread)

While experimental, this code is currently being served to users of [timetric.com](http://timetric.com) if they don't have Flash installed, and we intend to expose this to more users in the near future.