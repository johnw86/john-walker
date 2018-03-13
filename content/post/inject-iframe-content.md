---
title: "Inject Iframe Content"
date: 2018-03-13T21:11:31Z
draft: true
---

I recently had the requirement to inject the content of an email into an existing page of a website. The problem with just including the full HTML content of the email was that, if the included email included any CSS styles this would effect the actual website. I was seeing all links turning blue and being underlined for example which was a totally different style to the site itself. But as you can imagine this could cause all sorts of problems.

So thinking about the best approach to including this content I came to the conclusion an <code><iframe></code> would do the job. When using an <code><iframe></code> you would usually include a src url to embed within the frame. In this instance I did not have a url for the email content as I had the content available to me on the page.

After a bit of Googling I found that you can actually include a frame on the page and then set the actual html content for the frame.

https://codepen.io/johnw86/pen/rdxGBp
