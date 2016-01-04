---
published: true
layout: default
---






## My experience working with ServiceStack.NET

### Background

  As a developer, I think you are always on the path of trying to figure out how you can get from point a to point b faster, more efficiently and with less code. It is rare that you find a single tool that helps you with those 3 points (and MANY MANY more). Well, I have found that tool, for me. Now, welcome **[ServiceStack.NET](http://www.servicestack.net/)**.

  From the moment I started tinkering with the framework, I fell in love. I decided to use it on the next client project that I would be working on which started on December 7th. I decided to do this from the ground up, with only reading random tutorials found through the [ServiceStack.NET forums](https://forums.servicestack.net/), [pluralsite](http://www.pluralsite/) and [egghead.io](http://www.egghead.io) videos.

### Where is all of the config? 

A huge plus that servicestack offers is that there is no xml configuration, except the little bit that is required for the web integration. Most, if not all, of the framework allows you to configure things by conventions. I will give an example of this in the request / response service example [later in this article](#message-based-web-services).

### ?!? Message based web services ?!?

  The first concept that stood out to me was the whole **message based web services**. Being in the .NET arena for most of my career, I was very used to tightly-couple and large services that did many different things. With servicestacks implementation, each services is very focused. It has taken me quite a few hours of dealing with google, servicestacks wiki and other tutorials to really grasp how awesome message-based web services really are.

Let's get a small example of part of my current appplications implementation of servicestack. We have three parts to making the services work, the service, request and the response. Below is an example of each.

<div style="text-align: left">

####**_Request Example_**
![RequestExample.png]({{site.baseurl}}/_posts/RequestExample.png)

####**_Response Example_**
![ResponseExample.png]({{site.baseurl}}/_posts/ResponseExample.png)

####**_Response Example_**
![ServiceExample.png]({{site.baseurl}}/_posts/ServiceExample.png)

</div>

