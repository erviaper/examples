# Demo - background app that gets currently displayed ticket ID

Demonstrates autoLoad:false feature and client.trigger feature.

This demo shows:  
* Setting up events within background instance against location that use autoLoad:false
* Sending trigger events
* Using Apps framework `instances` methods
* Capturing when sidebar app is first created and subsequently activated

NOTE!: There are situations where the currently displayed ticket ID is *not* returned to the background app location. This happened when clicking 'Reload apps' and clicking multiple times on a ticket tab other than the one displayed before clicking 'Reload'.

## References
* Inspiration from [Apps framework v2 Instances demo app](https://github.com/zendesk/demo_apps/tree/master/v2/support/instances_sample_app)
