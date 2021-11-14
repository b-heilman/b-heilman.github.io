---
layout: page
title: About
permalink: /about/
---

This is my blog about how I think a modern API and UI should be written.  I'll be writing about my work on my personal projects that can be found [here][b-heilman].

I'm currently experimenting with monorepos and Typescript.  I understand why both concepts have been developed, but they feel like they solve one problem by introducing others.  Typescript is winning me over, but I haven't transitioned any of my libraries over to it yet.

[bmoor][bmoor] came about as a dream to fix how JS services and models were defined.  It tried to make defining those things simpler before ES6 was a thing and webpack with babel made using those features generally possible.  Now it's just a collection of libraries that I've found make my life easier.  Object get/set, logging, and error management are the primary ones.

[bmoor-cache][bmoor-cache], [bmoor-data][bmoor-data], and [bmoor-comm][bmoor-comm] were born of the dream to abstract the connection between the UI and the BE services.  They were perhaps a little too opinionated and the next iteration of them will be something that plays well with Angular, as that's my UI library of choice at the moment.

[bmoor-crud][bmoor-crud] is my very opinionated framework in how people should deal with data, much of it coming from a UI perspective.  It tries to approach API construction from an OO stand point.  Functionality defined on lower models are able to be combined into federated documents which combine multiple models in different shapes.

When I'm not coding, I've a fan of all Philly sports teams, talking economics, and debating politics.  I'll probably keep those topics out of this blog, but I'm sure one or two might slip in.

[b-heilman]: https://github.com/b-heilman
[bmoor]: https://github.com/b-heilman/bmoor
[bmoor-data]: https://github.com/b-heilman/bmoo-data
[bmoor-comm]: https://github.com/b-heilman/bmoor-comm
[bmoor-cache]: https://github.com/b-heilman/bmoor-cache
[bmoor-crud]: https://github.com/b-heilman/bmoor-crud