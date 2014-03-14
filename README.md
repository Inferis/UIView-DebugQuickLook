# UIView+DebugQuickLook

Provides an implementation for `debugQuickLookObject` for `UIView` objects.
It renders the view as an image and return that image to Xcode for inspection.

![Example](http://cl.ly/image/0n12410C260c/Image%202014-03-14%20at%2010.29.49%20pm.png)

## Features

* checks for existing implementation of `debugQuickLookObject` on `UIView`. Futureproofing = nice.
* automagically installs itself, no need to call methods
* only installs installs itself for `DEBUG` builds.

## Requires

* Xcode 5.1 or higher
* ARC
