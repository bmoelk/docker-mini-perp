# docker-mini-perp

Docker image that includes [perp](http://b0llix.net/perp/) v2.07 the "persistent process supervisor and service managment framework".

* FROM [mini/base](https://github.com/mini-containers/base)

While many docker images are designed to do one thing, there are 
some use-cases where having a single docker container do a 
handful of things is useful.

perp is a solid way of managing multiple processes. This is a minimal alternative 
to using [docker with s6](http://blog.tutum.co/2014/12/02/docker-and-s6-my-new-favorite-process-supervisor/).
The goal is to keep the image size small (17.33 MB).

Read these [perp man pages](http://b0llix.net/perp/site.cgi?page=manual):

* [perp intro](http://b0llix.net/perp/site.cgi?page=perp_intro.8) - overview of persistent process supervision
* [perpetrate](http://b0llix.net/perp/site.cgi?page=perpetrate.5) - conventions for runscripts

[Give it 5 minutes.](https://signalvnoise.com/posts/3124-give-it-five-minutes)

