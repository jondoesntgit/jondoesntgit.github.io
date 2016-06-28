---
banner_image:http://i.imgur.com/NpWoL4l.jpg
title:Solving Song Service Struggles
date:2016-06-27
layout:post
---


For at least the last 8 years, I have helped out with the primary division at the annual Wisconsin SDA Camp Meeting. Every day, my family and I lead out a morning and an evening program for the 7, 8, and 9 year olds. We also do games and crafts in the afternoon, totaling 37 hours of programming over the 9 days of Campmeeting.

A huge chunk of this time, often exceeding 90 minutes per day, is song pservice. We often take kids' requests and sing the dogs that they want to sing.

We show all the lyrics from a projector, and keep a PowerPoint with all the lyrics. This PowerPoint was easy to manage and the songs were easy to find when out repetoire was only 30 songs. But over the years, we have accumulated over 120 songs into a massive 300+ slide .pptx file.

With a file this big, several problems began to emerge:

- Although songs were organized alphabetically, sometimes songs would have multiple names and we would have a hard time finding the song based on name
- It would take  while to scroll to the slide where the song was
- parents wanted our slideshow, which was constantly under flux and update
- we often didn't know what key the song was in
- we would sometimes advance past the last slide of a song in the PowerPoint to the title slide of the next song
- power points do funny things when transferred to different devices

This year, I decided I was going to solve these problems. I did a Google search and found a JavaScript library called Lunr.js which indexes JSON documents for searching. I wrapped this functionality with jQuery and Bootstrap.
The result is an application that can load a directory full of MultiMarkdown formatted lyrics, and show them in a web app.

I programmed some keyboard shortcuts that help whoever was running the slideshow to pull up any lyrics in mere seconds. Furthermore, I coded a display so the musicians could see what key the song was in, and color coded the box so if they letter was blurry, they could tell by color.

The application was a huge success, and I uploaded it to the web, and placed an announcement in the Campmeeting Newsletter with a link to where they could use the app on my website at [labs.jamwheeler.com/primary-songs](labs.jamwheeler.com/primary-songs) and where they could download the program and all the lyrics to their hard drive for offline use from [GitHub](https://github.com/wheelerj/primary-songs).

![Song service on a boat!](http://i.imgur.com/kdZFT3H.jpg)

The tool came in more handy than I initially thought. Right after I uploaded it  to my website, the camp staff did a promo for summer camp by riding around in the camp boat singing songs. In years past, coming up with high-energy songs for 45 minutes and remembering what keys they are all in was a challenge. This year, we had it covered.

I believe this is a tool that can be used for all sorts of jam sessions and song services, and so I hope to extend it as time allows this summer to allow sheet music attachments, and even playing .mp3 files from within the app, so that Sabbath School leaders can sing primary songs even if they can't play guitar or piano.

If you found this useful, or have other suggestions, please send me some feedback via email or Facebook. I'd love to hear how this could be useful to you.