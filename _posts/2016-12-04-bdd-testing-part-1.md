---
layout: post
title:  "Is BDD Testing? A model for testers"
date:   2016-12-04 12:00:00 +0100
permalink: /bdd-testing-part-1/index.html
tags: BDD
image: /img/article/bdd.jpg
---

_Is BDD testing?  No. Well, some of the activities involve Testers, but it's not REAL testing, right?_

_Look! It's complicated!_

_Yes, yes! I know it's yet ANOTHER post on BDD, but we need to talk about this and I'm not here to criticise I'm here to understand so please bear with me!_

<h3>An Introduction</h3>

Sarcasm aside, Behaviour Driven Development is a big deal within software development and opinions on it are polarised.  BDD started to gain traction just as I started contracting as an Automation specialist so I have a lot of personal experience of going from a misguided sycophant who loved misusing BDD to an evangelised pitchfork wielding zealot who was convinced BDD would lead to the death of tester, and I've been back and forth over a period of five years.

Whilst I've mellowed out over those five years, I must admit until recently I took a dim view of BDD.  Especially as my approach towards automation in testing has evolved.  This resulted in a talk I gave at TestBash Manchester called 'The deadly sins of acceptance scenarios' and during it I was hardly singing from the rooftops about how great BDD is, as [Matthew Bretten](https://twitter.com/matthewbretten) noted:

> ...the negativity around BDD or acceptance scenarios feels like the negativity I’ve encountered around Microservices and I’d like to hear some well-thought out, positive experience reports. It feels like all of the balanced or thoughtful talks tend to be quite negative really and I don’t really see a great deal of value in using BDD over more straight-forward approaches such as TDD (Test Driven Development)...
> [http://bestofthetest.blogspot.co.uk/2016/10/testbash-manchester-2016.html](http://bestofthetest.blogspot.co.uk/2016/10/testbash-manchester-2016.html)

Matt's observation is correct in that it wasn't really giving the full picture of BDD and his comments resonated with some personal thoughts that I had on the subject at the time, namely:

'What is BDD exactly? Is BDD testing? or is it something else?'

<h3>Is BDD testing?</h3>

My inspiration for the talk was based on a frustration of seeing so many mistakes being made with automation in testing, which I blamed on developers and testers not truly understanding the proper use of Scenarios (Which I still believe is the case).  My intention was to highlight those mistakes, based on personal experiences, to show that others could use them as heuristics to help them see the traps they were falling in (which I still feel is useful).

But it was hard to talk to write.  As I began putting it all together I was surprised by how much it challenged my ideas of BDD and Scenarios.  I found my understanding severely lacking in places.  At first, it put me into a bit of a panic.   But with some support from awesome people who answered my questions, I began to rebuild my understanding of BDD.  However afterwards, I felt I was focused too much on Scenarios and so I set myself the following task:

__Immerse myself in BDD literature to help me understand BDD better.  Understand where testers' misconceptions have come from and build a model that would make BDD clearer for testers.__

And I have been.  And whilst I am by no means finished, I found creating it to be a very useful exercise.  For this post I simply wanted to share it so that others may find it useful, set them on the right path towards implementing BDD, and start a discussion.  I also hope it will help others towards avoiding the traps testers fall into with BDD. 

<h3>A model of BDD</h3>

So here is my model.  As you can see straight away there is a lot more to BDD than just Gherkin syntax and automation.  Over the next few blogs, I will describe in more details of the model and answer the question.  Is BDD testing? 

<img src="/img/2016/12/BDD-Model-1024x652.png" alt="Is BDD Testing? A model to help testers understand BDD better" style="width: 100%" />

For now, I am interested in hearing what people think about the model, so send me any feedback on Twitter on [@2bittester](https://twitter.com/2bittester)