---
title: "Contributing to Open Source"
categories: new
date: 2016-09-16
banner_image: http://i.imgur.com/lWLT6Lt.png
meta_description: "Today, I have arrived as a newly minted contributor to the open source world."
layout: post
---

A friend texted me a few months ago saying that he was officially an open source contributor. He explained that he had found a bug with some software that he was using, and was able to find the error in the source code. He made some modifications, committed the changes on a github fork, and then issued a pull request to the original author so that other users could benefit from it too.

I have been experimenting with a couple power user/productivity apps. The great thing about these apps is that they offer a lot of integration with other power user/productivity apps. Two such apps are [Fantastical](https://flexibits.com/fantastical) and [MailMate](https://freron.com/). When I see that an email contains date information that I want to put into my calendar, I can type a hotkey and it sends the message to Fantastical. Fantastical then uses its national language procesing engine to extract date, time, and other relevant information and drop it into my calendar.

Now, in a perfect world, this workflow would do what workflows for Omnifocus, Evernote, and others would do. However, I noticed that the created Fantastical event had a misformed url. When I clicked on the 'show event in mail' link, my mail client didn't know what to do about it. Upon closer inspection, I discovered that the link was missing a '<' and '>' around the message ID. A little bit of code sleuthing revealed the line of code responsible, and with an addition of a few characters, everything was made right on my computer.

"But wait," I said, "there may be others with the same problem." So, I found the GitHub repository where this bundle was hosted. I forked the project so I could make changes. I then commited the changes to the miscreant line of code and pushed them back to GitHub. Then, I returned back to the original repository and issued a pull request asking for the code to be put back into the main repository.

This is a process that I had always heard about. When I was growing up in high school, I heard about these big projects that were open source, and was able to see other people contributing to them. I dreamed of one day getting enough software skills to one day make contributions that could help others. Today was that day.

Granted, this feels like a very small contribution, but Confucious say, journey of 1000 miles begins with single step. In my case, single line of code.