![Head JS](http://headjs.com/media/img/headjs.gif)

[http://headjs.com](http://headjs.com)

## Differences ##

This extended version of Head JS is also capable of loading stylesheets. `head.js` has been renamed to `head.load` to
reflect the new functionality.

## Gotchas ##

There is no consistent and reliable cross browser implementation for the onload event on link elements. Therefore
Head JS just mimics the missing functionality by always invoking the callback function after 300ms.
