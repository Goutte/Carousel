Carousel
========

![Logo](http://github.com/Goutte/Carousel/raw/master/Docs/carousel.jpg)

This is a simple carousel that uses existing DOM Elements.



How to use
----------

Build your carousel the way you want, style it, and then apply the javascript on it.
The carousel will change the width of the first child of the carousel element and manipulate its margin-left.
The other style properties stay untouched.


HTML

``` html

<a id="prev" href="#">&lt;</a>

<span id="carousel">

  <ul id="carouselContent">
    <li>1.</li>
    <li>2.</li>
    <li>3.</li>
    <li>4.</li>
    <li>5.</li>
    <li>6.</li>
    <li>7.</li>
    <li>8.</li>
    <li>9.</li>
    <li>10.</li>
    <li>11.</li>
    <li>12.</li>
    <li>13.</li>
    <li>14.</li>
    <li>15.</li>
    <li>16.</li>
  </ul>

</span>

<a id="next" href="#">&gt;</a>

<div id="counter">
    <span id="counterCurrent">0</span>
    /
    <span id="counterTotal">0</span>
</div>

```


JAVASCRIPT

``` javascript

// Create the Carousel objet
var carousel = new Carousel('carousel',{
  prevButton: 'prev',
  nextButton: 'next',
  counterCurrent: 'counterCurrent',
  counterTotal:   'counterTotal',
  nbOfColsPerPage: 3,
  nbOfRowsPerPage: 2,
  onLast: function(){
    // nothing
  }
});

```



Demo
----

http://jsfiddle.net/goutte/jkeLe/


Thanks
------

FOSS lovers everywhere <3