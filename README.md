# Infinite Carousel

_Timed infinite carousel that uses vanilla JavaScript & CSS animations. It supports both horizontal and vertical scrolling. It's useful if you need a UI element to continuously scroll (ex: ticker being displayed on a TV monitor)._

## Install

### Download

+ CSS:
  - [infinite-carousel.css](https://github.com/jonchretien/infinite-carousel/raw/master/dist/infinite-carousel.css)
  - [infinite-carousel.min.css](https://github.com/jonchretien/infinite-carousel/raw/master/dist/infinite-carousel.min.css)
+ JavaScript:
  - [infinite-carousel.js](https://github.com/jonchretien/infinite-carousel/raw/master/dist/infinite-carousel.js)
  - [infinite-carousel.min.js](https://github.com/jonchretien/infinite-carousel/raw/master/dist/infinite-carousel.min.js)

## Usage

Infinite Carousel works with a container element and a set of child item elements.

``` html
<div class="infinite-carousel-shell">
  <div id="container" class="infinite-carousel-group">
    <div class="infinite-carousel-group-item">1</div>
    <div class="infinite-carousel-group-item">2</div>
    <div class="infinite-carousel-group-item">3</div>
    <div class="infinite-carousel-group-item">4</div>
  </div>
</div>
```

### Options

``` js
var infinitecarousel = new InfiniteCarousel('#container', 'horizontal', 3 {
  // options, defaults listed

  timerDuration: 2000,
  // set time between advances in milliseconds

  transitionDuration: '1s'
  // the duration of the animation
});
```

## Browser Support

Tested in the latest versions of:
+ Chrome (v41)
+ Firefox (v36)
+ Opera (v27)
+ Safari (v8).

## License

Infinite Carousel is released under the [MIT license](https://github.com/jonchretien/infinite-carousel/blob/master/LICENSE.txt).

## To Do
+ Tests
+ Docs
+ Demos