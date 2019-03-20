# bio

Scott Triglia is a Tech Lead at Yelp and loves making large backend systems reliable and effective. He helped architect Yelp's nearby recommendation engine, was the lead maintainer of business and search geocoding, and lead Yelp's Commerce Platform for payments and billing. Currently he is technical lead Yelp's advertising group.

# presentations
Talks I have given

## Arrested Development - surviving the awkward adolescence of microservices

> The potential upside of microservices is significant and exciting. So much so that Yelp’s Transaction Platform committed from the start to an architecture of small, cooperative microservices. This talk explores the inevitable complications that arise for Python developers in as the services grow larger and stretch both their own architecture and the developers responsible for them. Come hear tales of terror (tight coupling! low test coverage!), stories which will warm your heart (agility! strong interfaces!), and everything in between as we follow the adventures of our plucky team.

> The talk will be focused on the functional, cultural, and reliability challenges which occur as a microservices-based project evolves and expands over time. Particular attention will be paid to where these diverge from the utopian way microservices are often described, and to the particular difficulties faced by Python developers trying to implement such systems. My goal is to share with attendees some mistakes we’ve made, some successful methods for growing gracefully, and Python-specific tools/libraries which can help with these problems.

Given at:

* Europython 2015 - https://www.youtube.com/watch?v=z3_HorshzJ4 (["One of the top 5 presentations", says BlueYonder](https://blog-e.blue-yonder.com/europython-the-five-best-presentations/))
* PyconAU 2015 - https://www.youtube.com/watch?v=H0KReHUawHI

## Working effectively with legacy code -- python edition

> Legacy code is that terrifying monster lurking in almost every long-lived codebase. You may not understand it, you may wonder how it works at all! It is the type of code most developers do their best to stay away from, and for good reason. So what is there to do when you inherit such a system for the first time? How can you take it from unknown mess to gleaming example of excellent engineering? What is unique about legacy systems written in Python?

> This talk will present a series of tools, both technical and social, for rehabilitating unknown, untested, and maybe even unloved systems. Approaches to improving these systems will primarily focus on refactoring and testing, with sidebars on engineering culture and personal motivation. We will reference Michael Feathers's excellent book on the topic, but also depart significantly to discuss particular challenges and opportunities presented by the Python language. After all, much of the written literature on this topic assumes a fairly Java-centric view of the world, and offers little support when you realize that object you thought was a dict is actually an ORM model that just happens to support getattr lookup.

Given at:

* PyDX 2015
* Pycon Canada 2015 - https://www.youtube.com/watch?v=RMt43wyg-zg

## Protecting your users with Circuit Breakers

Description:

> The inevitability of failures is the bane of scaling any modern web service and can be a deal breaker when the API failing is something you depend on! Lucky for us, there are techniques that can help protect your product and handle failures in subsystems gracefully. This talk will dive into one of these in depth, the Circuit Breaker pattern, and explore the options it gives us for keeping our users happy when APIs are failing.

> We will be focusing on several real-world problems and how they can be addressed by circuit breakers. You should expect to leave the talk with details on simple circuit breakers as well as understanding how they can be adapted for more complex situations.

Given at:

* VanPyDay 2016 - https://www.youtube.com/watch?v=x6b7U9GpfQk&t=1h10m45s
* Europython 2016 - https://www.youtube.com/watch?v=vdS88uyGayM ([rated 4.5/5 stars](http://imgur.com/a/Vj3Sl))
* API World + Integrate 2016
* ConFoo Montreal 2017 ([rated ~4.8/5 stars](confoo_circuitbreakers_audience_feedback.pdf))

## Crystal clear service interfaces with Swagger/OpenAPI

> Learn how to better communicate between Python services. We'll use simple-to-follow examples and go from a service with undocumented endpoints to one which has full docs and validation on requests. Learn how to use Swagger tooling for python, including the bravado (client) and pyramid_swagger (server) libraries. In the end, you'll (hopefully!) find nirvana and make the machines do all the hard work for you.

Given at:

* ConFoo Montreal 2017 ([rated ~4.8/5 stars](confoo_swagger_audience_feedback.pdf))

## From monolith to serverless with Amazon Step Functions

Sometimes it seems like you can hardly go a day without hearing about how “serverless” is going to change the world of backend architecture. But aside from toy proofs of concept, how are you realistically supposed to put it into practice? Most of us work with years-old codebases that are resistant to decoupling, much less easy to transition to serverless.

Come hear how Yelp has been moving a 10 year old codebase from tangled spaghetti toward a serverless future using AWS Step Functions (SFN). You’ll gain familiarity with SFN as infrastructure, learn how it can be used to effectively disentangle complicated systems, and understand how to incrementally introduce serverless components into your monolithic application.


Given at:

* PyGotham 2017 - https://www.youtube.com/watch?v=UeYHJISlWgk
* PyTexas 2017
* Re:Invent 2017 (CMP319)

Accompanying blog post: https://engineeringblog.yelp.com/2017/11/breaking-down-the-monolith-with-aws-step-functions.html

## Surviving (and thriving!) when you are overloaded

Taking on leadership roles always includes new demands on your attention and time. Inevitably, your finite work week will conflict with the sheer amount of tasks you have to do. How can we as leaders keep stepping up to new responsibilities while balancing our pre-existing ones?

This talk will focus on strategies for managing a too-large workload without abandoning important tasks or doing a shoddy job. We’ll look at techniques to prioritize what work matters most, identify tasks we should be doing ourselves, and finally delegate the rest to build our team’s skills while reducing our own workload.

Given at:

* Pycon US 2018 - https://www.youtube.com/watch?v=dWuRDbH4Xlw

Mentioned as one of the best talks at Pycon https://medium.com/civis-analytics/pycon-2018-a-roundup-of-our-favorite-talks-7a9ab3628f9d and https://klaviyo.tech/experiences-of-a-team-at-pycon-2018-68851a4117d6.
