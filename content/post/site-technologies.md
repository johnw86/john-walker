---
title: "Site Technologies"
date: 2017-07-25T20:58:54+01:00
draft: false
images: ['img/site-technologies/twitter-card-hugo-logo.png']
---

As the new site has been put together on new platforms I had never used before, I thought a post about this may inspire others to give them a go also.

## Hugo

The website itself has been developed with the [HUGO](http://gohugo.io/) framework. 'Hugo is one of the most popular open-source static site generators. With its amazing speed and flexibility, Hugo makes building websites fun again.' To be honest until last week I had not even heard of HUGO. I came across it reading an article about how [Smashing Magazine will be using HUGO](https://next.smashingmagazine.com/2017/03/a-little-surprise-is-waiting-for-you-here--meet-the-next-smashing-magazine/) for their new website 

The article had me intrigued as the idea of re-building my website had been in the back of my mind for a while. I followed the really simple [quick start guide](http://gohugo.io/getting-started/quick-start/) and realised how quickly I could potentially get something up and running.


### Steps 

It really was a simple as:

- Install via Chocolately (package manager)
- Create a new site via the cmd line
- Select and download theme from the gallery
- Configure site settings

That's it, you then have a simple templated site you can run up locally and start thinking about content.

## Hosting

As HUGO is a static site builder you can host your static content on pretty much any service. They also provide guides on some of the more popular platforms like; GitHub, Firebase, BitBucket and others. 

As I already use a lot of services from Google and had no experience of Firebase, I looked into that as a potential option first. On review of their pricing I saw that I could host for free, with my custom domain and even a SSL cert on the Spark plan.

In order to deploy my new HUGO site to Firebase the steps were:

- Login to Firebase with my Google account and setup a new project
- Install the Firebase tools
- Login and initialise my project via the command line
- Deploy with a single command

Now every time I write a new post and want to push it live I just need to run a single command. 

## Early impressions

I was certainly impressed with the speed in which I managed to go from no website to a new themed blog all deployed in just over an hour. For anyone like me who is looking to put a basic blog together, which they want to write content in Markdown, I don't think you can really go wrong with HUGO.

{{< tweet 888407323038842880 >}}

