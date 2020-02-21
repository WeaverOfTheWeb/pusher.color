pusher.color
============

A mirror of http://tech.pusherhq.com/libraries/color [Offline]

Will set c to "rgba(105,80,131,1.0)"
```javascript
var c = pusher.color('packed_argb', -9875325).html()
Or if you wanted a different format:
```
```javascript
var colorObject = pusher.color('packed_argb', -9875325);
var htmlString = colorObject.html();          // i.e. "rgba(105,80,131,1.0)"
var colorName  = colorObject.html('keyword'); // closest named color
var hexString  = colorObject.html('hex6');    // "#695083"
```
