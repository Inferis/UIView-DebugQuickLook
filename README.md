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

## Further reading

Check out [LLDB-QuickLook](https://github.com/ryanolsonk/LLDB-QuickLook), which provides the same (and more) for lldb.
No need to add the file to your projects, but you have to install it on each machine. Also, works a bit different.
