Carousel
========

![Logo](http://github.com/Goutte/Carousel/raw/master/Docs/carousel.jpg)

This is a simple carousel that uses existing DOM Elements.



How to use
----------

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