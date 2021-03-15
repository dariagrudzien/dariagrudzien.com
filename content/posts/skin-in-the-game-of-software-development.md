---
title: "Skin In The Game Of Software Development"
date: 2021-03-15T14:01:58+02:00
featured_image: "/img/amy-hirschi-uwpo02K55zw-unsplash.jpeg"
---

**Or The Agency Problem Within Engineering Teams.**

___

A while back I decided it's time for a change and went to find my second engineering adventure. As I've been enjoying a month off in between the
jobs and subjecting myself to the brain dump of Nassim Taleb's [Skin In
The
Game](https://www.goodreads.com/book/show/36064445-skin-in-the-game)
I realized there's one main learning I got both out of the job hunt and my
first job:

**TL;DR --- Engineering work suffers if technical decision makers
don't participate in experiencing the consequences of their decisions.**

Let me illustrate with these examples[^1] :

**Team ABC:**

This team is responsible for helping developers deploy and operate their
software. When asked about the biggest challenge they are facing they do
not mention Kubernetes scaling issues (be honest, that's what you
expected to read here, right?) but instead explain being stuck with the
architects. Apparently it's not uncommon for the architects to make
design decisions which Team ABC knows upfront will lead to operational
issues down the (pretty short) line.

The Team ABC, not being able to convince the architects to amend their
designs, watches the changes being implemented, bake for a while, and
take down the production. Team ABC helps mitigate and hotfix the issues,
goes back for round two of discussions with the architects and spends a
lot of energy trying to get a systems design that will actually work.

**Team XYZ:**

Team XYZ is in charge of developing and operating a cloud native
infrastructure service Alpha. They get temporary backup from engineers
from another team to deliver new functionalities. Those engineers come
back from the project and share their surprise of finding out that
service Alpha does not have local development environments or a
comprehensive end-to-end testing suite. This recently resulted in
downtime or service impairment caused by the deployment of the new
functionality developed by the temporary backup engineers.

To explore the potential for relieving some engineering pain and
improving production stability Team XYZ is asked about the lack of the
local environments. One of the voices mentions those were not
prioritized in the roadmap due to the belief of some of the decision
makers that all engineers deploying to production should understand
their changes well enough to avoid any deployment issues[^2] .

The follow up question to establish the agency and power dynamic comes
naturally --- "When was the last time said decision makers deployed code
to production?" --- and earns a good round of chuckles.

Now let's take a step back and look at some references.

**Skin In The Game**
====================

The aforementioned Taleb uses the following distinction to explain the
asymmetry of risk taking (I selected my favourite one out of a list,
which I believe ---with a grain of salt--- to be least Taleb-style
biased and most representative of the idea):


> ***No skin in the game***: Keeps upside, transfers downside to others, owns a hidden option at someone else's expense --- e.g. bureaucrats, policy wonks.
>
> ***Skin in the game***: Keeps his own downside, takes his or her own risk --- e.g. citizens.
>
> ***Skin in the game of others, or soul in the game***: Takes the downside on behalf of others, or for universal values --- e.g. saints[^3], knights, warriors, soldiers.

Taleb then follows with a host of examples and anecdotes about finance
executives taking their bonuses after tanking the very banks they were
leading in 2008, consultants who don't get to experience the
consequences of their own advice, or politicians who cut education
spending while sending their kids to private schools.

The main point Taleb is making is as follows: asymmetries in the risk
taking within a society or organisation lead to creating rotten systems,
in which people don't suffer the negative consequences of their
decisions, and therefore are not properly motivated to care about those
consequences, i.e. they don't have the "skin in the game".

**Hit Pause**
=============

You may feel like saying "Well, we've got a lot of work to do and we're
short-staffed, so there's no time for philosophizing about motivations
and incentives". If you're tempted to say this I'd urge you to pause for
a second and consider these:

1\. What is the cost of downtime of service impairment for your business?
Say you're business-critical systems have been at 99.9% availability
last year and half of that downtime (roughly 4.3 hours) was due to a bad
design decision. How much did it cost your company?

2\. You've got 10 engineers on your team. Your engineers can't spin up a
local development environment and instead have to deploy their work in
progress to a shared environment, spending half a day instead of 5
minutes to inspect the effect of their code changes on the whole system.
How much of their salary is wasted coordinating lengthy deploys into
test environments weekly, monthly, yearly? How much is that costing your
business?

3\. You have your architect, senior SRE and a senior Dev struggle to come
to an agreement on system design in a two hour meeting. This happens
twice a month, and still does not prevent the downtime. How much does
that affect your bottom line?

All this is to say that taking the time to reflect on and improve the
alignment of your team on high development velocity with minimal risk of
downtime will pay for itself. It is not just affecting how much people
like working with each other (which isn't necessarily
business-critical[^4]), it's directly affecting the very job they were
hired to do --- to serve the customers and bring value to the business.

**Consider The Alternatives**
=============================

Bring the skin to the game of decision makers by having them deploy code
regularly, or by giving them a pager and adding them to the oncall
rotation. Watch how their decisions change when they know they may be
the ones waking up at 2AM to resolve a production incident.

If for some reason it's not possible for them to participate in the
regular development work or on call rotation, then at least make sure
that "removing engineering pain" is a part of their performance
evaluation.

Beware of handing the bulk of the decision making power to people who
are not participating in the everyday engineering work. Their
incentives, motivations, and goals may hinder your whole team's
productivity.

[^1]: These examples are very good illustrations of something I've
    observed in multiple teams I spoke with or interacted with
    throughout the past 3+ years. My intention is not to shame anyone
    who may recognize this dynamic in their own work experiences.

[^2]: Now imagine my chagrin when I ended up listening to a talk given
    by one of them on the topic of operational excellence and the
    importance to catching bugs before they make it to production.

[^3]: As I said folks, take it with a grain of salt.

[^4]: Now that I think about it, the trust and respect people feel for
    their coworkers directly affects the excellence of their work by
    creating the atmosphere of psychological safety as described by the
    [State of The DevOps Report from
    2019](https://services.google.com/fh/files/misc/state-of-devops-2019.pdf).
    Not to mention how it affects retention and hiring budgets.

_**Daria**_

*P.S. Many thanks to Lukáš Linhart for his review and corrections.*

![Banner](/images/dg-tcp-2.jpeg)
