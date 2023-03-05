# Varnish

https://varnish-cache.org/_static/varnishcache_rgb-gimp2-alpha.png

# The basics
Varnish Cache is a web application accelerator also known as a caching HTTP reverse proxy. You install it in front of any server that speaks HTTP and configure it to cache the contents. Varnish Cache is really, really fast. It typically speeds up delivery with a factor of 300 - 1000x, depending on your architecture. A high level overview of what Varnish does can be seen in this video.

# Performance
Varnish performs really, really well. It is usually bound by the speed of the network, effectively turning performance into a non-issue. We’ve seen Varnish delivering 20 Gbps on regular off-the-shelf hardware.

# Flexibility
One of the key features of Varnish Cache, in addition to its performance, is the flexibility of its configuration language, VCL. VCL enables you to write policies on how incoming requests should be handled. In such a policy you can decide what content you want to serve, from where you want to get the content and how the request or response should be altered. And, you can extend Varnish with modules (VMODs). You can read more about this in our tutorial.
