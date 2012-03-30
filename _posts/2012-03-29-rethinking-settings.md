---
layout: post
title: Rethinking Settings
---

Today, I fixed two problems for my girlfriend involving Gmail:

1. The Mail app on her iPhone wasn't fetching mail from her Gmail
account and kept complaining about having an incorrect password.
2. Whenever Gmail fetched emails from her Princeton email address, it
stored them in All Mail instead of Inbox.

For the first problem, we stumbled across the solution by accident --
we had tried a million different "solutions" suggested on various
forums and Google Groups and decided to change her password
temporarily so that it didn't take so long to enter her password into
her iPhone every time we tried to link her account. I happened to see
that she had
[2-step verification](http://googleblog.blogspot.com/2011/02/advanced-sign-in-security-for-your.html)
enabled when we went to her Google Account settings (not her Gmail
settings) and asked her to turn it off for the time being to see
whether it fixed our problem. It did. It turns out that the Mail app
on the iPhone can't ask for verification codes and so Google generates
application-specific passwords for your account.

For the second problem, I went to her Gmail settings and found that
she had enabled the option to archive all mail fetched from her school
email address. Boom. Problem solved.

Through this experience, I saw Gmail and Google account settings with
fresh eyes and realized just how confusing and overwhelming they are
for the average user. Gmail has many features, and every feature
introduces more settings for the user to manage. Enabling 2-step
verification alone forces you to manage 6 more settings! There are
three settings for receiving codes (mobile application, backup phone
number, printable backup codes), one setting for application-specific
passwords, and two advanced settings for clearing the phone info and
printable codes and managing trusted computers.

![2-step verification settings](http://i.imgur.com/p7UES.png?1)

Oh, and you need to go to your Google Account settings to change these
settings, even though it's perfectly understandable why someone would
look under Gmail settings. After all, if you're unable to fetch email
from your Gmail account, you would think it's a problem with Gmail. As
for turning off the option to archive all emails fetched from another
address, it might be clear to power users that this setting would be
located under Accounts > Check mail using POP3, but it wasn't that
clear to my girlfriend.

How can we make settings simple for feature-rich applications like
Gmail without hurting the power users? Hiding the advanced settings in
order to clearly show the most commonly used ones wouldn't work
because the power users wouldn't be able to easily manage the advanced
settings.

There's a better way. A similar problem exists for application menus,
and
[Mark Shuttleworth's HUD](http://www.markshuttleworth.com/archives/939)
offers a simple solution to that problem. Imagine having a similar
look-ahead system for applications with a lot of settings. You would
type what problem you're experiencing or what setting you want to
change, and the application would parse the query and display the
pertinent settings. If you're a power user who knows exactly what
setting you want to change, the auto-complete would save you time by
taking you directly to the setting instead of making you click around
the settings page. With this system, you can skip the entire step of
searching for solutions and know exactly which settings may affect the
behavior you're experiencing. For example, if my girlfriend were to
type "iphone gmail incorrect password" into this settings query box,
Google would know that 2-step verification could cause a problem with
mobile application and display the setting to add an
application-specific password. This would provide a much better
experience than searching through settings tabs and countless forums,
hoping that the next random suggestion might solve your problem.
