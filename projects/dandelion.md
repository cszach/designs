---
layout: post
title: 'Dandelion'
---

During DandyHacks 2021‒University of Rochester's premier annual hackathon‒my
team and I gathered to come up with an epic mobile app. We called it
_Dandelion_‒a mobile app for crowdsourcing community service. How it works is,
any user can post a community service (like planting trees at a local park, say)
as well as choose an existing community service to work for. The more you
dedicate yourself to community service, the more points and achievements you
collect.

So I guess you can kind of think of it as a volunteer job finder, or LinkedIn
for unpaid jobs, haha.

Except, we wanted to keep the app simple to use. I was the only guy in charge of
spitting out UI designs, and the prototypes below were what I came up with.

{% include image.html image="projects/dandelion/explore-find" %}

This is the main "job search" interface. It is a slippy map and it was supposed
to be populated with clickable pins, each one for a posted job. Somehow I did
not add them to the design and just told the front-end fella, "There are going
to be pins here." And he certainly [did that](https://youtu.be/_tF-cQTbUSc). At
the top there is a search bar, if you are familiar with Google Maps. The grey
circle is a boilerplate to be replaced by the user's profile picture.

See the green tree icon? It means the search is filtering by environment-related
jobs. Yes, we came up with a list of categories for different volunteering jobs.

{% include image.html image="projects/dandelion/types.png" %}

There it is.

{% include image.html image="projects/dandelion/explore-job.png" %}

Once you have found a job, this pops up at the bottom. You can slide it up to
get…

{% include image.html image="projects/dandelion/job-details.png" %}

…this! Cool, huh?

I want to point out the "500 pts/hour" detail. That is kind of like the hourly
reward, or "salary", you get for participating in the volunteer effort. What we
do to the points, I'm not entirely sure.

{% include image.html image="projects/dandelion/account-popup.png" %}

Onto my favorite part of the design project. This is what you see when you click
on your profile picture in the search bar, or really, viewing anyone's profile.
Similar to the job details component, the user profile component does not fully
take up the screen right away, but just appears nicely at the bottom. Don't ask
me why I used the [Disappointed Muhammad Sarim Akhtar](https://knowyourmeme.com/memes/disappointed-muhammad-sarim-akhtar) in the prototype design; I figured it was
cool to have a little fun with the designs.

{% include image.html image="projects/dandelion/account-full.png" %}

This is the full view. The background is dimmed so the user can focus on the
user profile information.

{% include image.html image="projects/dandelion/login.png" %}

This is what I came up for the login screen. Nothing fancy, just two text
fields. Looking back, I am not sure why I used a terribly low contrast. Take,
for example, the checkbox next to the "Organization" text. Can you see it? It is
barely visible. I guess that's what we call "modern graphics design".

Oh, you are wondering about the circle. Right. It's a placeholder for the app's
logo. I'm pretty sure we didn't come up with one at the time I designed this,
so, ladies and gentlemen, behold…the splash screen:

{% include image.html image="projects/dandelion/splash.png" %}