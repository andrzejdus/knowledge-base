#### Ideas
* shapes
* background patterns
* clip-path
* link underlines in css - http://tobiasahlin.com/blog/css-trick-animating-link-underlines/
* will-change property

#### Hacks
* IE8 rgba equivalent
```css
background: #000;
-ms-filter: "progid:DXImageTransform.Microsoft.Alpha(Opacity=80)";
```
This doesn't allow clicks to go through transparent element, contrary to `filter: progid:DXImageTransform.Microsoft.gradient(startColorstr=#CC000000,endColorstr=#CC000000)`

There is also an issue with jQuery and fadeIn/fadeOut method which resets ms filter opacity to (respectively) 100/0.
