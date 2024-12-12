---
# You can also start simply with 'default'
theme: default
background: knot.jpg
# some information about your slides (markdown enabled)
title: Design System Success
info: |
  ## Design System Success

  A talk by Will Klein. Learn more at https://www.willklein.co/
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
# transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true
---


<!--
So this talk wasn't originally a part of the schedule, but I volunteered it yesterday in the event that another speaker wasn't able to make it here. Unfortunately, this was the case for someone, and I want to recognize their hard work to prepare for this conference, and let's send them some good vibes that they are feeling better and they are missed.

Thank you all for welcoming me on short notice, I am also sharing a talk on testing this Monday on the Remote Day, but I came her in-person because I've heard such great things about the community here. I appreciate the chance to share another topic near and dear to my heart.

With that said, I have a story to tell...
-->
---
layout: image
image: flatirons.jpg
---

# Boulder, Colorado, USA
## March 2018


<style>
  h1 {
    color: #000;
  font-weight: 600;
  font-size: 64px;
  line-height: 64px;
  }
  h2 {
    color: #000;
  font-weight: 600;
  font-size: 48px;
  line-height: 48px;
  }
</style>


<!--

There's this beautiful and iconic geographic feature called the Flatirons. If you live or work in the city of Boulder, you can see it from anywhere.

Back in March 2018, I started working in Boulder, and I could see it everyday I went to work.

I joined a big tech company to work on a flagship project. The kind of thing that moves the stock price.

Where I worked really doesn't matter, it could have been anywhere, and in fact, I've seen these lessons on other projects, other teams, and seen them resonate in the experiences of other developers I've talked to.

our challenge in this case though, was to improve the UX for over 60. MILLION. users.

-->
---
layout: image
image: flatirons.jpg
---

# Boulder, Colorado, USA
## March 2018


<style>
  h1 {
    color: #000;
  font-weight: 600;
  font-size: 64px;
  line-height: 64px;
  }
  h2 {
    color: #000;
  font-weight: 600;
  font-size: 48px;
  line-height: 48px;
  }
</style>

<!--
This was an enterprise app, where a hundred products were shuffled together into a single frankenstein of a user experience.

and back in 2018, "conversational UI" was still trending, so we set out to build a chat assistant to help save to our users.

our mission was to make the most common tasks in our app possible in a few brief messages using our AI assistant. our team would deliver a UI component that would exist everywhere, all the time, in the app.

floating in the bottom right corner of every web page, and taking one of four navigation icons in our mobile presence.

it would be ubiquitious.
-->

---
layout: image
image: flatirons.jpg
---

# Boulder, Colorado, USA
## March 2020


<style>
  h1 {
    color: #000;
  font-weight: 600;
  font-size: 64px;
  line-height: 64px;
  }
  h2 {
    color: #000;
  font-weight: 600;
  font-size: 48px;
  line-height: 48px;
  }
</style>
<!--
And after two years building and shipping our little chat bubble, we had succeeded in almost every measure.

Over 60M users

no major issues or bugs

and it some things really easy to do, quickly, like submit a time off request in just a couple chat messages

we _did_ it
-->
---
layout: image
image: missing-piece.jpg
---

<!--
But there was a hidden failure behind the scenes

for such a pivotal element of our user experience, we had shipped it without including a critical resource

...

We weren't using our design system.
-->

---
layout: image
image: paper-dark.jpg # crumpled paper image here (todo)
transition: fade-in
---

<!--
While our product had won,
our design system had lost.

My team did not consult it for guidance. We did not rely on its design components in Figma, and our frontend ignored its tokens and React components.

Our UI design was good, but at what cost.

If our design system was to evolve, we wouldn't change with it. Instead of building a bridge to a more cohesive visual experience, we potentially made the problem much worse.
-->

---
layout: image
image: paper.jpg
transition: fade-in
---


<!--
after seeing ours fail, I want to tell you

-->
---
layout: image
image: paper.jpg
transition: fade-in
---

<br>

# What Makes
# a Design System Win

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

# Will Klein

<!--

what makes a design system win
-->


---
layout: image
image: zoom.jpg
---

<!--
I was the senior UI developer on our product, so why hadn't I used our design system?

It was at the beginning of the pandemic when I joined the Zoom call for the design system montly demo. It had been on my calendar for over a year, and it was maybe the second time I was attending.

I liked what I was seeing, their work was good, but I didn't have a clear way to connect their work with mine.
-->

---
layout: image
image: bump.jpg
---

<!--
I was friends with the design system team too.

they open sourced the design system a year earlier, which I was very excited see

meanwhile, i had gotten our company to sponsor our first javascript conference, which _they_ were excited to see.

We both believed in sharing our work with the broader community, in giving back, in sharing what we love.
-->

---
layout: image
image: hire.jpg
---

<!--
I had played a major role in shaping this team as well.

I had recommended they hire two of my friends - both of whom I met from meetups and conferences.

They would become co-leads on the project.
-->

---
layout: image
image: phone.jpg
---

<!--
As the pandemic began, I needed a change for myself. I was experiencing the longest period of burnout in my entire career, and it was only getting worse.

I thought about trying a different kind of work, I looked at the design system problem, and I took a chance on a wild idea.

I was on parental leave wondering what I would do to turn my career around, when I asked their manager, Lynn, if he would jump on a call with me.

I brought up my experience NOT using their system.

and, I wanted to change things for not just my current team, but our entire UI community. I wondered what could happen if we got people *excited* about the design system.

I also told him how I was burned out - and - he would be taking a real risk if he hired me. I had never worked in developer relations. I knew frontend, but I did not know design systems.
-->

---
layout: image
image: bulb.jpg
---

<!--

Despite my warnings - he was all in. He got to work creating headcount and a new role that never existed before. I remember he sent me an empty document to create my job description.

Four months later, I joined the team as their very first design system developer advocate.

Now before I continue any further in the story, I need to be very clear about something.

This team I was joining ... was exceptional. They were already doing an amazing job, but this was a very large software company, with over 12,000 employees at this point, and it would only grow from there.
-->
---
layout: image
image: bridge-frame.webp
---

<!--

My experience as a non-consumer wasn't their fault, but a symptom of a common challenge across many design systems at growing companies.

This is also a common challenge in areas outside of design systems, in platform engineering teams, and really, anytime you produce code (or design) that other teams depend on, it can be a battle to win over consumers and earn their adoption.

It is extremely likely that if you haven't already, you will encounter this kind of challenge in your career, design systems or elsewhere.

Getting the attention of busy product developers is hard.

Keeping their attention is hard.

It's already hard enough to build a great design system, in terms of code and design.

Good luck doing that and winning the attention game.
-->
---
layout: image
image: glass-2.webp
---

<!--
When I started,

I really had no idea what I was doing.

At least, it felt that way, but I had some gut feelings about what I needed try.

-->

---
layout: image
image: building.jpg
---

<!--

Past Me was was the problem the Present Me needed to solve.

Past me was focused on my team's mission, too busy to check out the design system.

There _were_ other product teams using our design system, but there were all too many that were apathetic.

They didn't know, they didn't care.
-->

---
layout: image
image: good.jpg
---

<!--
I love this quote from the American actor Steve Martin.

But what makes a design system THAT good. So good, it's impossible to ignore.

Our design and our code were both very good. As good as you would hope, and as we would deliver my first major release the following May, 2021, I truly believed they were excellent.

Something else needed to change.

-->

---
layout: image
image: help.jpg
---

# Be so *helpful* they can't ignore you

<style>
  h1 {
    background-color: #000;
    font-size: 54px;
    line-height: 54px;
  }
</style>

<!--

This didn't start with me - our team was already showing up in every UI conversation they could find.

If someone asked about React, web fundamentals, or TypeScript, someone was there to answer questions. It wasn't even about supporting the design system. We had UI experts, and they were showing up whenever they were needed.

This wasn't about telling people to use the design system either.

It was about being helpful. Being helpful builds trust.

Building trust builds reputation.

And of course, if someone had a design system question, we were on it as fast as someone saw it

and often, two or more developers from our team were in the conversation to show support.

I got to see the questions grow in frequency, with more people joining our design system developer channel in Slack.
-->
---
layout: image
image: listen.jpg
---

<!--
One thing we believed, was if someone had a problem using our design system, that meant there was something we could improve.

Maybe our docs weren't clear enough. We were missing a code example. Our usage guidance needed improvement. Our component API wasn't flexible enough.

Sometimes it was simply user error, but we always greeted them with:

"i'm sorry, that should work better for you. let's figure this out together"

Before long, our generous sharing of expertise, coupled with an ever-friendly and gentle attitude, meant that our Slack channel started to fill with questions, often not about our design system, but we didn't care. People were asking for help, and we were happy to provide it.

-->
---
layout: image
image: trojan.jpg
---

<!--
When our fifth major version came out in May of 2021, I would give my first release demo. We had significant changes to our component API.

We bet the house on compound components. We would make our components not rigid and fixed, but flexible and adaptable.

We didn't expect everyone to understand this change though. Our code examples went from a single line to sometimes 30 lines of JSX.

We exposed more inner workings of our components. Taking advantage of this meant a paradigm shift for our developer community.

I also really like teaching,

so we created a trojan horse.
-->

---
layout: image
image: bulbs.jpg
---

# Workshops

<style>
  h1 {
    background-color: #000;
    font-size: 64px;
    line-height: 80px;
    width: 340px;
  }
</style>

<!--
During our demo, we announced our first workshop: an introduction to compound components. Its focus was on React patterns and how access to the underlying DOM elements was a more powerful way to use our API.

I didn't say it was about the design system, because at its core, it really wasn't.

Of course we would use our design system components in the example app, and carefully layer many of our new components across our lessons.

The true objective and measure of our workshop's success was if we could level up developers across the company.

We had so many sign ups we offered it twice and reached a staggering percentage of our product teams.

I would give it again the following spring, and less than a year later with three new members of our team, we unveiled a new workshop that taught the fundamentals of responsive design with our latest components.
-->

---
layout: image
image: lifeguard.jpg
---

# Office Hours

<style>
  h1 {
    background-color: #000;
    font-size: 64px;
    line-height: 80px;
    width: 380px;
  }
</style>
<!--
Between these workshops, we kept the conversation going regularly in two ways.

Every week, we hosted office hours. At first we tried sign ups, and that worked, as some folks like to schedule face time with us to get support.

Most often though, we were on a walk-in basis. I would post in our Slack channel that office hours had started, and I'd either make a dad joke or suggest we chat about the latest news in frontend. SOmetimes it was just me hosting it, but often, a couple more folks from my team would join, and we'd hang out and ask each other questions.

Then our consumers would join, and it would get so busy that I would create breakout rooms in Zoom to work on everyone's questions in parallel.

After a while, we developed a group of regulars.

folks would join and just hang out. it felt like a club, one that welcomed anyone and everyone. if they didn't have any questions, I'd just ask them what they were working on and we'd learn more about the problems our product teams were solving, which is great for understanding what problems we needed to solve.
-->

---
layout: image
image: on-air.jpg
---

# Release Demos

<style>
  h1 {
    background-color: #000;
    font-size: 64px;
    line-height: 80px;
    width: 460px;
    right: 50px;
    position: absolute;
  }
</style>
<!--

The other way we kept up with everyone was with our release demos.

We started on a monthly schedule with every minor version, but we saw two things happen.

First, we had a few months were we didn't have that much to share, not because we weren't busy, but because much of our work was rolling into the next major version. we developed a strategy... (edit)

Second, as the company grew from around 10,000 employees to around 16,000, we could see meeting fatigue really set in.

So we dialed it back to every six months, to match our major release schedule, and dialed it up to be even more polished and prepared.

-->

---
layout: image
image: calendar.jpg
---

# Release Schedule

<style>
  h1 {
    background-color: #000;
    font-size: 64px;
    line-height: 80px;
    width: 280px;
    text-align: right;
    right: 50px;
    position: absolute;
  }
</style>

<!--
We also created a predictable release schedule that was mapped out months in advance.

Major releases would arrive roughly 6 months apart.

The May release would intentionally have more breaking changes, while the fall release would be less impactful, but still significant with new features.

This built more trust with our consumers, as we showed we were predictable and
-->
---
layout: image
image: up.jpg
---

# Adoption

<style>
  h1 {
    background-color: #000;
    font-size: 64px;
    line-height: 80px;
    width: 290px;
  }
</style>


<!--
So...

what did this do for adoption?

well, while I was tracking demo attendance and Slack statistics to track our community, my friend Alan was measuring component usage and what version of our library was installed by each product, month by month.

Not only did we see our adoption grow and accelerate, but Alan led the effort to reach out to product teams directly, to make sure they knew how we could help them ship faster using the design system, and also find out why some projects were years behind on their library version.
-->
---
layout: image
image: package.jpg
---

# Dependencies...

<style>
  h1 {
    background-color: #000;
    font-size: 64px;
    line-height: 80px;
    width: 500px;
  }
</style>
<!--
It turns out there was significant lag between when we released a major version, and when teams would update their dependency and take advantage of the latest and greatest.

Early on in my tenure, we had a brainstorm session on what would go into our v5 release in the spring of 2021. I knew how tedious it was to manually edit potentially hundreds of lines of code in a repo, just to update a single dependency. Dependency management was painful, no matter how you went about it.

We were moving to compound components too, and that often meant expanding one line of JSX into many more.
-->
---
layout: image
image: wood-tools.jpg
---

# Tooling

<style>
  h1 {
    background-color: #000;
    font-size: 64px;
    line-height: 80px;
    width: 240px;
    position: absolute;
    right: 50px;
    bottom: 50px;
    padding-left: 15px;
  }
</style>

<!--
So I asked: what if we shipped code mods in v5? We could automate many of our breaking changes.

A code mod would automatically rewrote code using our previous version, to use the new version. It could significantly reduce developer effort in applying an upgrade.

Our team went for out.

This would become a staple of every major release from then on

Breaking changes? Yes. Thousands of lines of code impacted across the company? Ummm, yeah. You can apply this in minutes? OHHH yeah.

-->
---
layout: image
image: mic.jpg
---

# Learn how!

<style>
  h1 {
    background-color: #000;
    font-size: 64px;
    line-height: 80px;
    width: 330px;
  }
</style>
<!--
OK, quick timeout, I'm giving a workshop tomorrow on how to write your own code mods. it may be full, but we added 10 more spots. check tomorrow in case a spot opens up

-->

---
layout: image
image: path.jpg
---

# A Clear Path

<style>
  h1 {
    background-color: #000;
    font-size: 64px;
    line-height: 80px;
    width: 370px;
  }
</style>

<!--
We didn't just ship code mods, but rich upgrade guides.

They were called migration guides, but I made a subtle change to call them upgrade guides - hoping that would give the impression it wasn't as dramatic a change. We didn't want to scare anyone with the perceived effort.

We clearly spelled out in every guide what components were impacted.

We described how this would affect design and visual presentation.

We described how it would change the implementation in code.

We noted if there was a code mod, which couldn't always be done, but happened for almost everything.

And in our release demos, we wouldn't just showcase our new components, but walk through the impact of every change.

I remember an office hours session where someone joined to ask about updating their library from 4 versions back. We did a screen share, opened up our upgrade guide, and I went and ran the code mods. We bumped to the next version, and I ran the code mods again. They were so impressed, they asked to end the call, they wanted to try the last two upgrades without me, assisted by the upgrade guide and our code mods.

A half hour later, they told me they were done, and their product was all caught up. We had moved them up four major versions in well under an hour.

It's hard to upgrade a dependency when you don't know the scope it will entail.

Having code mods and clear upgrade guides simplifed this to the smallest effort possible.

-->
---
layout: image
image: fire.jpg
---
# Crisis

<style>
  h1 {
    background-color: #000;
    font-size: 64px;
    line-height: 80px;
    width: 370px;
  }
</style>

<!--
Remember our Slack channel?

It tripled in size over 2 and a half years.

We continued to field questions and challenges that were intended for other teams, but there was a moment where this came up very unexpectedly.

Our platform engineering team used @channel to ping our entire community about a required React version upgrade, and how it was happening in a month's time - actually leaving a number of teams scrambling, with no free time to handle it.

We had the biggest UI channel in our company's Slack, so yeah, if you want to get the word out, you _could_ @ mention everyone.

Which - we never did. We always made our announcements shiny but concise. We would say "more details are in the thread" with only the most interesting parts mentioned in the initial message.

We considered everyone's time and attention to be precious, so we made sure every message to our community was well-crafted and thoughtful.

But when this React dependency grenade went off, we jumped on it. We believed it would have a consequential impact on our consumers, even if we weren't the cause. Some teams were quite upset, they had their own deadlines and milestones established, and this was coming from a place they didn't expect.

I remember joining a call to help one of those teams, I invited the right folks from the platform team too, they did _not_ attend, and after 30 minutes the product team would realize:

it wasn't the design system team that had made the call on the React dependency change. they were mad at us at first, because the way the platform team had announced it, in our channel, it made it seem like we were the ones responsible.

We were coming from a very different place of support and compatibility too. We supported the new version of react I think about a year in advance of this

and we continued to be backwards compatible with the previous version for some time after. But we cared that their concerns were heard and understood, and while we might not have pulled the pin on the grenade, we were there to put it back.

when they figured out where we stood in all of this, the conversation shifted. our reputation wasn't just repaired, they left that call with even more respect for us.
-->

---
layout: image
image: point.jpg
---

# Advocacy

<style>
  h1 {
    background-color: #000;
    font-size: 64px;
    line-height: 80px;
    width: 300px;
    position: absolute;
    bottom: 50px;
    padding-left: 10px;
  }
</style>

<!--
Over this time, we established many friends through office hours, demos, and jumping on calls whenever people asked.

Over this time, we would hear from new people we never heard of before, and they would tell us what other people _they_ respected were saying about us.

Keep in mind, we were never "mandated" for product teams to use. We had to earn our place in their tech stack. And earn it we did. But what really got us there, couldn't be the effort of a single developer advocate, or even our entire team.

It was our friends that were advocating FOR us, behind their own closed doors, around the world in Canada, the bay area, Ireland, and other offices around Europe. We heard about it quite a lot - and I think it's safe to guess, it was happening even more than we knew.

At times, we saw it for ourselves in Slack channel.

We also saw folks help out more and more. I facilitated dozens of open source contributions from outside our team. And questions in our channel were getting answered by other community members, without our team needing to respond.
-->

---
layout: image
image: fireworks.jpg
---

<!--
In May of 2023, I gave my last release demo, it was themed around boy bands from the late 90s, we had a playlist with NSync, and Boyzone. We dressed up, we made it a party.

I gave my last workshop a couple days later, and completed seven other projects that month to send things off.

If there's anything I hope you'll gather from this talk, I hope you see it's not the design or the code that will make a design system.

Those things are important, and critical, and I wish they were enough.

But what will make the difference isn't how good we implement, or even deliver. It takes something else beyond technical excellence.
-->
---
layout: image
image: heart.jpg
---

<!--

I hope we build communities that are warm, and helpful.

I hope we build tools to help other developers, and spend hours of our time to save them many more.

I hope we make friends that we share our time and energy with generously.

I hope we have fun, I hope we make it a party.

I believe, that's what make a design system win.

-->
---
layout: image
image: thank-you.jpg
---

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />


## <carbon-logo-x /> @willklein_

## <carbon-link /> willklein.co

## <carbon-lightning /> toolspace.dev


<style>
  h1 {
    /* background-color: #000; */
    font-size: 64px;
    line-height: 80px;
    width: 300px;
  }
</style>

<!--
I now work on developer tools full-time at Toolspace, a consultancy I started earlier this year.

I'm here if you ever want to talk about design systems or internal developer relations. Please don't hesitate to find me online, in-person, I'd love to hear what you're working on, what your challenges look like, and explore how we can improve the developer experience for all of us.

Thank you.
-->
