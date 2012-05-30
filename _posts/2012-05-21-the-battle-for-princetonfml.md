---
layout: post
title: The Battle for PrincetonFML
---

For the uninitiated, PrincetonFML is an FML site directed towards the
Princeton community. It was launched as one of many college FML sites
created by a Harvard student under the company
[CollegeFML](http://www.linkedin.com/company/college-fml-llc).
(Ironically, Harvard is one of the few schools that doesn't use a
CollegeFML FML site.) As anyone can see from visiting
[princetonfml.com](http://princetonfml.com) or
[collegefml.com](http://collegefml.com), both websites (and all the
other CollegeFML sites) are down. I don't think anyone really knows
what happened.

When the website went down a week or two ago, the impact of its
absence was noticeable in the Princeton undergraduate community. The
topic of its breakage was brought up in numerous conversations, and
that's when I realized that I had to make a clone.

I quickly nabbed the domain ptonfml.com and got down to work. Even
though we were nearing exam week, making this website became my top
priority. Why? I knew that the longer I took to make the site, the
more people would get used to not having an FML site -- and in the
worst case, someone else on campus would get the same idea and make
their own replacement.

And that's exactly what happened. A day into working on the site, I
saw this post on Facebook:

![pfml.me announcement](/images/pfml_announcement.png)

Fuck. Someone had beat me to it. The page took forever to load and the
upvote/downvote functionality didn't work, but it was something. I
flipped to release-as-soon-as-possible mode because I knew that the
longer I took to make my version, the more the other site would gain
popularity without competition.

Six hours after I saw the post, I typed 'git push heroku' and
[ptonfml.com](http://ptonfml.com) went live. My upvote/downvote system
let anyone vote multiple times if they refreshed the page and I had
slapped on Disqus last-minute to allow visitors to comment, but it was
something. I posted the site as my Facebook status and waited for
visitors. Over the course of the night, more than 700 visitors came to
check it out. Not bad. I started feeling pretty confident and thought
that being second to launch wasn't so bad after all.

Then things took a turn for the worse. The
[Daily Princetonian](http://www.dailyprincetonian.com/), Princeton's
student-run newspaper, had caught wind of the other site's launch and
had released a
[piece](http://www.dailyprincetonian.com/2012/05/17/30983/) on it
being the "new PrincetonFML". Damn it. I was paying the price of not
being first. Although a bit discouraged that the other site was
getting a ton of free publicity, I was determined to make my site the
superior option. After all, the other site was just an exact clone of
the previous website -- a simple theme slapped on top of a Wordpress
install. I had coded mine from scratch using Ruby on Rails. That had
to count for something, right? People would care that my site loaded
in the low hundreds of milliseconds whereas the other one loaded
upwards of five seconds, right?!

Some of my readers are probably laughing by now, because they know the
truth: users don't give a shit. As long a website is Good Enough,
they're highly unlikely to switch to anything else. However, despite
the fact that the Prince (Daily Princetonian) featured the other site,
my site continued receiving healthy amounts of traffic. It definitely
helped that the first comment on the Prince article was a link to my
site.

So where am I four days out? Today, someone submitted this as their
FML post:

> No one cares about this website; it clearly lost the traffic battle
> to the other pfml website. Being stubborn != successful business
> model #pivot

This was obviously not an FML submission, but someone trying to send
me a message. Over the past couple days, I've gotten used to receiving
hate posts (examples: "This site is not impressive. FYL" and "This
site is pretty lame. FYL, mods.") I found posts of this nature so
amusing that I accepted them and had them displayed on the site.
Haters gonna hate.

But this latest post was less an attack on the website itself and more
a claim about something I've put a lot of thought into: which site
will become the de facto PrincetonFML. Ultimately, only one will
remain.

Is the claim in the submission true? It's entirely possible that the
other site has been receiving more traffic after being featured on the
Prince. All I know that I'm still getting hundreds of hits, and the
number of users is growing. Am I losing money hosting the site? No.
(Thanks, Heroku!) Is this a business? Hell no. I built something for
fun, and I'd say that it's been fairly successful. If I'm stubborn
about anything, it's about making my site the best it can be. I have a
pretty big vision for where a site heavily frequented by the Princeton
community can go. So if you're planning on telling me that my website
sucks and that it's not going to be a successful business, I'd like to
kindly tell you to fuck off.

I don't know whether my site will continue to be successful and grow
or if the other site will end up winning this battle to replace
PrincetonFML. If anything, I've gained experience and had a ton of fun
seeing this go from conception to launch in a few days. Here are my
major takeaways:

1. If you want to make something quickly, a great option is Rails +
Bootstrap + Heroku. You can create a functioning, presentable website
in mere hours.

2. Launch early and improve quickly. Even though I originally had
Disqus comments that required users' emails (users hated it) and my
voting system was broken, I am glad that I launched when I did. If
anything, I wish I had launched earlier.

3. Fuck the haters. Don't let anyone discourage you when you're
putting in your hard work to make something awesome.

Update (5/29/2012): CollegeFML and its sites have been restored.

