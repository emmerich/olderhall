---
layout: post
title:  "2 years of Scrum in a startup"
date:   2018-11-01 22:14:00 +0200
categories: agile
---

Two years ago, I took on the CTO role at [Wuha](https://wuha.io). Our development team was 2 people, myself included, and we wanted to expand to 10.

Even when we were 2, we were Agile and using Scrum. However, Scrum at 2 people and Scrum at 10 people isn't the same thing and we had to actively evolve to accomodate the new staff.

This post is a memoir for myself so that I don't forget the lessons I've learned, and hopefully it gives you ideas on how to identify problems or improve things in your team.

# Should I have done formal training before managing the team?

My previous experience of Agile, specifically Scrum, was purely as a developer on an Agile team. I have done no formal training in Agile/Scrum.

I don't know whether formal training before taking on a project like this helps or not. [The Scrum Guide](https://www.scrumguides.org/scrum-guide.html) is a fantastic source of information and the rest you learn on the job.

Scrum changes a lot from company to company, and so having hands-on experience is definitely necessary. You can gain that through employment, as I did, or through workshops with practical activities. Don't sign up to a purely theoretical course on Scrum or Agile, it's so easy to learn online with the guide and a few videos.

If having this list of "must read" resources is something you're looking for, and you can't already find it, please email me and I'll put something together.

# It's more efficient to have a technical Product Owner

I am the Product Owner, but also the technical lead on the project. I'm capable of prioritizing the Product Backlog based on the business requirements, as well as being part of the technical breakdown. This works well.

Having a purely technical Product Owner with no business vision doesn't work - you take on a huge risk that the Backlog is not correctly prioritized according to the business needs.

It's fine to have a non-technical Product Owner. The benefit of being a technical Product Owner is that I was capable of understanding the technical side and measuring the "technical difficulty" of stories whilst prioritizing the Backlog. I know whether a story is going to take days or months to implement, and can react accordingly.

**Important Note**

If you're technical and the Product Owner, don't do the Sprint Planning yourself. You might be perfectly capable of breaking down stories into individual tasks, but you'll lose out on having a shared understanding of the Sprint and the exercise of breaking things down into manageable chunks. Don't do it!

# Team members should have a crash course in Scrum as part of their onboarding

One thing we should have done from the first hire is to give a crash course on Scrum for each team member. Scrum, to me, is second nature, it's just "the way things are done in software".

However, as previously mentioned, Scrum differs from business to business, and so a crash course explaining "this is how we do things here" helps everyone. Not only that, but hiring fresh graduates who didn't have a practical explanation of Scrum makes is necessary.

Take each recruit and show them how Scrum works **in your business**. Show them the Backlog, explain what you do as a Product Owner and how demos work. You'll be giving them a headstart and making sure the whole team is on the same page.

# You don't need a Scrum Master

We don't have a Scrum Master and we don't have the resources to hire one. In fact, if I met a startup of 10 people with a full-time Scrum Master, I'd be worried.

If everyone on the team commits themselves to learning Scrum and understanding the benefits, you probably don't need to hire one before 100 employees.

Having said that, I send regular Slack messages saying "move this ticket into the correct status", or re-explaining how Scrum works and its benefits, so I guess I am the Scrum Master. Just roll it into your Product Owner.

The Scrum Master is Scrum's answer to "how do we make sure everyone's playing by the rules?". In a perfect world, every member of the team would have a good basic knowledge of Scrum and know the benefits. Unfortunately that's not the case, and I am still searching for a way to promote Scrum within the team without specifically hiring for it. Email me!

# I'm not sure if explicit Sprint Goals are necessary

Normally in Scrum each Sprint is designed with a Goal. I've never worked in an environment where the Goal has been explicitly defined - the Goal for me is to finish what's in the Sprint. I guess you could define our Sprint Goal as always being "advancing the product".

However, we do occasionally have team members who say "well I'm not quite sure where the company is going short-term". Maybe having Sprint Goals would help alleviate this problem, at least on a month-by-month basis.

# We do the Daily Scrum over Slack

Despite being one of the easier aspects to understand, this is one of our more talked about subjects.

We started with a daily standup at 9AM where everyone would present what they did, what they're doing, and whether they'll be blocked. It took about 15 minutes.

Getting everyone physically in a room, to speak for only 1 minute, proved surprisingly difficult. Remote work, vacation, people turning up late (not right but sometimes unavoidable) all impeded the standup. If the standup was pushed back 10 minutes, that would disrupt the morning for the people who arrived earlier.

We tried different approaches - one big standup, a standup of teams of 3-4 people, we changed the time. In the end, we decided it was the physical aspect that proved difficult and we started to use Slack.

**insert image of standup on Slack**

Every morning at 9AM Slack reminds us to write our daily updates. People who arrive at 9:35AM can write their update on the bus. People who arrive earlier can write their update straight away and get back to work. Slack's tagging makes it easy for people to know if they're needed by another team member. It also means people outside of the Development Team can check in without disrupting.

In the end this approach really improved things - people are still aware of what others are doing but they are free to organise their mornings to be the most productive possible. I'm currently looking at Slack Apps that help make this process easier (I sometimes have to chase people up to do their update).

# Don't underestimate the importance of QA

I want to talk about QA, because I think this caused several problems that I incorrectly attributed to Agile development.

We don't have a dedicated QA team. Each developer tests their own code locally, and once it's pushed to a staging environment it's the job of another person to test that feature for functionality and business acceptance.

This is a mistake. We should have hired a tester. At 10 developers, you need a dedicated tester - maybe even 2. Our team are working fast and pushing out features very quickly, and need someone dedicated to making sure the quality doesn't drop.

So we've had to adapt. That's normal. Within a startup, everyone does things that they haven't done before. I, along with the non-technical team, perform acceptance testing. Other developers test at the implementation level.

The problem is that we're not experts in testing. We had personality clashes between people that did not want to test or did not have the patience to test and the developers.

We didn't push bad code, but we didn't have a formal procedure for QA. Stories and bugs would stay in the staging environment untested for days because there was no responsibility. It was not a good environment to work in and it put pressure on the team each release.

We are fixing this by being assigning responsibility to a dedicated tester for each task (instead of just leaving it open). Our next technical hire will be a tester. You live and learn.

# How we handle unexpected work

We often had urgent work that would come in mid-Sprint. Ultimately we discovered that this was due to one of 2 problems:

* Bad Planning - not being able to anticipate upcoming business requirements and panicking when a client asked for something that wasn't ready.
* Bad QA - saying that something is "done" and pushing it when it's not properly tested or validated.

By improving communication between the Product Owner and the clients, we improved our planning process. By improving testing and QA, we reduced the number of critical bugs coming into the Sprints.

Fixing things in production is stressful. The house is on fire and you're trying to douse the flames whilst people are walking in the front door. No magic formula here unfortunately, I found it to be common across startups, but it's important to identify and work as a team to support each other so that one person doesn't feel like the "firefighter" of the team.

# The importance of the Sprint Demo and the Sprint Retrospective

One of the bigger regrets I have is not believing in the Sprint Demo. My very inexperienced mind thought "the team is using the product every day, there's no need for a demo". This was a huge error.

Demoing is incredibly important because it **gives an individual piece of work an owner**.

I mentioned that we had problems with QA - features that were not adequately tested. If that developer had had to perform a demo of the functionality in front of the team or a user, I'm sure that they'd have taken more care over the implementation.

Demos are a very efficient way of communicating at a high level. It's difficult to get a global view of what people are working on via the daily standup because it's very specific and isolated to a window of 24 hours. The demo lets the developer say: "you remember all of those daily updates? Well this is the end product".

Retrospectives are important too - we didn't do very many - but I learned that we were asking the same questions in an indirect or individual way. We're starting to perform retrospectives in groups and leaving one-to-one meetings for personal feedback.

# Don't anchor product releases to Sprints - you don't need to

The Scrum Guide talks about defining the word "Done". A task within a Sprint should be "Done" by the end of the Sprint. My interpretation of "Done" was "the task is implemented, deployed, and tested in production". **This is wrong.**

Assuming that we would deploy to production every 2 weeks created enormous pressure to have something ready to go. We would awkwardly plan work just so that we could squeeze it into the release. In the end, we were driven by our release calendar and not by our work.

In the end we delayed over half of our 2-weekly releases because things weren't "Done" - and every single time it felt like a failure. I remember working 4 weekends in a row thinking "this will never end". That's not a good working environment.

I went back to basics and spoke to as many people as I could about why I had this problem. In the end, it came down to my incorrect interpretation of "Done":

**Not every Sprint ends with a production release.**

I'm currently working on defining a release procedure that isn't tied to our development Sprints. It'll still be Agile and on the same cycle as development, but decoupling release Sprints and development Sprints removes that pressure that everything has to be production ready on Thursday night.

Sprints are driven by time, releases are driven by value.

Release when you have something to release, not just because it's the end of a Sprint.

# Final Remarks

## Get everyone onboard

When you adopt Scrum, you do it for the whole company, not just the developers.

Everyone should be ready to learn - even those not working directly with the development team. It's important to understand how Scrum works, what a Sprint is, how to report a bug or a feature request so that it plays nicely with the Product Owner.

## Focus on the methodology, not the tools

Scrum is a methodology. It doesn't matter what tools you use as long as your team is productive and you're advancing. Don't buy into software thinking it's necessary to do Scrum, you can do Scrum with a pen and paper.

## Easy to use, difficult to master

Scrum is easy to get started with and brings a lot of value just with the basics. However, as experience and time shows, it's difficult to perfect. There are always differences between companies and its important not to think "we're doing it wrong". It's a methodology, not a step-by-step guide.

Scale Scrum to your team. Do the minimum until you feel friction, then review how things work and evolve.

Don't be afraid of going to your team and saying "we did this before but it's not working and we're going to change". I was too scared in the beginning to change things because I thought it would reflect badly on me and my ability to manage, but that's ridiculous. As the team and business evolves, your software development needs to evolve too.

You'll meet a lot of people from other companies who say "oh well we do things like that". Cool, it works for them. As long as your development team are motivated, efficient, and aligned with the vision of the company, just keep moving forward.

Thanks for reading,

Steven