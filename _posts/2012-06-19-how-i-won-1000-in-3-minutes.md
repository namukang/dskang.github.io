---
layout: post
title: How I Won $1000 in 3 Minutes
---

A week ago, I competed in via.me's [XHack 2012](http://xhack2012.com)
and was fortunate enough to win the People's Choice $1000 prize. If you
ask anyone who was there, they'd tell you that I won solely based on my
three minute demo. Here's how I did it, and I hope that these tips will
help those of you who also get a kick out of building things at
hackathons.

## Show, don't tell

This tip is the most important one, and that's why it's first. It's also
the most obvious. But for whatever reason, people just seem to forget
that no one wants to listen to a PowerPoint presentation about how cool
a hack is. They want to see it with their own eyes and judge for
themselves. Your goal should be to get your hack in front of the
audience as quickly as possible. Show them your hard work.

## Explain why your work matters

Although you should be striving to show your hack as quickly as
possible, sometimes it makes sense to give a backstory about why you
made what you did. In my case, I talked about how difficult it was to
post a picture on [via.me](http://via.me/), which provided the
motivation for making a Chrome extension that would allow a user to post
a picture to the site with a single click. The explanation took about 30
seconds, and it allowed me to provide some background before
demonstrating my app.

## Don't go into too much detail

My hack was a simple [Chrome extension](http://instavia.me), and that's
all I told the audience. I didn't mention the great [OAuth2 library for
Chrome extensions ](http://smus.com/oauth2-chrome-extensions/) that uses
a neat workaround in order to work with redirect URIs. I didn't mention
how I used [XHR2](http://www.html5rocks.com/en/tutorials/file/xhr2/) to
grab images and upload them directly to via.me.  Implementation details
are boring; what matters is the result.  You only have a couple minutes
on stage.  Don't put your audience to sleep.

## Do it live

Decide what the coolest part of your hack is, then do it live. In order
to demonstrate how big of an improvement my hack was over the existing
system, I asked via.me's Director of Product to participate in my demo.
I brought up a random picture and asked him to upload it to via.me, the
catch being that there would be a stopwatch timing how fast he could do
it. As he rushed to upload the picture, I narrated how much trouble the
user had to go through in order to upload a single picture: right click
to save the picture, decide where to save it on the hard drive, navigate
to via.me, look for the upload button, navigate the file system again in
order to locate the downloaded picture, and then finally click upload.

By the time the picture finally uploaded, 1 minute and 49 seconds had
passed. Then it was my turn. I started the stopwatch, clicked on my
extension, and finished uploading in under five seconds. The audience
loved it.

## No excuses

If your demo doesn't work and it's your fault, don't make excuses.
Especially don't say that it worked 5 minutes ago on your local machine
and that you can prove it by demonstrating it to any interested parties
after the demo. Unfortunately, even though you're probably telling the
truth, it doesn't change the fact that your demo is not working when
everyone is able to see it in action. Just explain what it should do,
and focus on the parts that do work. If nothing works, then just laugh
it off and blame it on the demo gods. It happens to the best of us.

## Have fun

If nothing else, you probably learned a couple things along the way and
met some smart hackers. Even if you don't win, you should be proud of
the fact that you were able to build something completely new from
scratch in a very limited time frame. After all, that's what makes
hackathons so fun in the first place.
