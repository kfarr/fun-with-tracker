# fun-with-tracker
Playing with A-Frame and the HTC Vive Tracker with multi user examples. Highly experimental and will break at any moment without notice.

Requires:
* PC / Windows with WebVR compatible browser that supports vive trackers, right now that is only Firefox Nightly
* HTC Vive
* Vive Trackers
* Smart Phone Mount (recommended: https://www.amazon.com/gp/product/B01L3B5PBI/)
* Your phone or another spare smartphone that can support webvr using polyfill (any reasonably recent smart phone). Android phone required for passthrough camera trick.

Firebase Examples:
* server.html - run this first on a PC with HTC Vive and at least one running Vive Tracker
* client.html - use on mobile phone connected to a tracker
* clientp.html - same as above with attempt to show passthrough camera for an augmented reality like experience (Android required)

Instructions:
* You may want to substitute your own firebase credentials. Make sure your firebase projects allows for anonymous connections and your db is open read and writes. This is obviously not secure at all.
