# (Whisk) Mixpanel JavaScript Library

## Important!

This is a Whisk fork of the original Mixpanel JavaScript Library.

This version differs from the main library in two important ways:

0. We provide a namespace to load the library into, which can be specified. It will not be `window` unless you explicitly set `namespace = window`.
0. We remove the asynchronous loading. This is because we need synchronous loading.

## Original README

The Mixpanel JavaScript Library is a set of methods attached to a global `mixpanel` object
intended to be used by websites wishing to send data to Mixpanel projects. A full reference
is available [here](https://mixpanel.com/help/reference/javascript).
