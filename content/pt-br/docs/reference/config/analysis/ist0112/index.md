---
title: VirtualServiceDestinationPortSelectorRequired
layout: analysis-message
---

This message occurs when a virtual service routes to a service with more than one port exposed, but does not specify which one to use. This ambiguity can lead to undefined behavior.

To fix, add a `port` to the virtual service [Destination](/pt-br/docs/reference/config/networking/virtual-service/#Destination) to disambiguate which service port should be routed to.
