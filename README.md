# Physical dimension breakpoints

This project shares a list of many media queries for different physical dimension of many devices.

## What is this?

There are two common terms known while working with media queries, `width` and `device-width`.

According to the [MDN documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries),

about **width**

> The width media feature describes the width of the rendering surface of the output device (such as the width of the document window, or the width of the page box on a printer).

about **device-width**

> Describes the width of the output device (meaning the entire screen or page, rather than just the rendering area, such as the document window).

**What is the difference between the two, `width` and `device-width`?

> Many tablets and mobile devices don’t always have 1 device pixel per CSS pixel. The iPhone 4, for example, has 2 device pixels per CSS pixel. For reference, you should know that the iPhone 4 has a regular screen layout viewport of 640×960. This means that, in this example, the device-width of the iPhone4 is 320×480. This is the case because Apple realizes that not every website is built responsively (shame on them) and tries to please everyone by having around 980px width to accommodate the desktop view of the website. This means, that if there is no meta viewport tag in place, the iPhone4 will take your website, render it as if it were 980px wide, squish it into a 320px display, and as a result, would be zoomed out to the user.

[*Quoted from SitePoint article*](http://www.sitepoint.com/media-queries-width-vs-device-width/)

## Table of Contents

* [iPhone](iphone)
* [iPad](ipad)
* [Samsung Galaxy](samsung-galaxy)
* [Samsung Galaxy Tab](samsung-galaxy-tab)
* [Nexus](nexus)
* [HTC](htc)
* [Kindle Fire](kindle-fire)
* [Apple Watch](apple-watch)
* [Motorola Watch](moto-watch)


## Have devices that not listed here?

If you find any device that is not listed here, [make an issue with detail](https://github.com/petehouston/physical-dimension-breakpoints/issues).

## References

* [CSS Tricks - Media queries for standard devices](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/)

## Contribute

Feel free to fork the project and [send pull a request](https://github.com/petehouston/physical-dimension-breakpoints/pulls).
