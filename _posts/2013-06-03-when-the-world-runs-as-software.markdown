---
author: Matt Oswalt
comments: true
date: 2013-06-03 14:00:00+00:00
layout: post
slug: when-the-world-runs-as-software
title: When The World Runs As Software
wordpress_id: 3899
categories:
- The Evolution
tags:
- open source
- sdn
- software
---

I have heard so many sweeping statements in the past few weeks like "network engineers' jobs are in danger" or "will my CCIE have any value when networking is run in the hypervisor"? Clearly the social media community is preaching "software or bust" these days, clearly leaving those that are not used to this kind of talk, or have been doing infrastructure the same way for years, quite alienated. I want to make one thing extremely clear - **It's okay to be an infrastructure person**. This skillset is not going anywhere, despite what some completely ill-informed articles might say.  It will simply evolve. It is **not** okay to be an infrastructure person that is also not open to change. Infrastructure will have a physical presence, but it's administration, it's scaling properties, and even best practice design will change to address evolving business demands. Let me provide some perspective.

I'm close with someone who owns a small business that provides consulting services on products like SAP, where a customer demands a SME on how the software works, and Layer 7 stuff like data migrations from dev to prod. Neither party gives two craps how the infrastructure works. Neither party cares about the plumbing. They may have a few VMs in Rackspace, but they don't know what Openstack is, nor should they. They just care about apps, because those are what they do, and that's what brings home the bacon. As a fellow infrastructure person, I want to reiterate that it's okay to not be this way; there's plenty of room for people that care about the infrastructure  - that care about the technical differences betwen vBlock and Flexpod. However, at the end of the day, the infrastructure's main purpose is to run applications, and if it can't do that efficiently, or change with flexibility, then there's a problem.

Hanging on to the old way of doing things is what's going to keep perpetuating this "me vs. you" mentality, which is a dated, unproductive, and costly mentality to have. Right now the apps people are pretty pissed off that every change they need to make requires a request to the "evil infrastructure team", which will undoubtedly cause some irate emails, work stoppages, and all manner of technical discussions that go nowhere because neither team knows how to communicate with each other.

When you see a blog post saying grand, strange statements like "the network of tomorrow will be configured in Eclipse", you might get a little squeemish. I know I did at first. Keep in mind that there will always be a physical network. Sure, a lot of functions are moving into the hypervisor, but something will have to connect the hypervisors together.

The key here is to remember that the applications people are waiting for the network to catch up to demand. Not scalability or capacity so much, but **flexibility** (which is actually a superset of scalability and capacity anways). Flexibility in being able to provision a certain slice of infrastructure within minutes, seamlessly. Flexibility in being able to make a policy change across a massive global infrastructure immediately, and seamlessly. The application people don't care about the plumbing. They don't care about changing the oil in a car, just that the car is able to get them from point A to point B, or to point C if needed. The point is that the infrastructure needs to be smarter, and more agile, so that the apps people don't have to worry about coming to us for a change request. It's time to get out of the way - it's time to stop this "us against them" mentality.

Stepping out of the philosophy and into reality, this is the driving factor behind wanting to do everything in software. It's the reason why commodity hardware driven by open source software (or at the very least open standardized protocols) is so attractive to the bleeding edge technologists right now. These are all building blocks of the infrastructure of tomorrow, because they give us the tools to define exactly what our network needs to do, and change on a whim, when the applications demand it.

Where does this leave the average infrastructure-VAR out there? Most VARs out there that deploy network, compute, storage or even virtual infrastructure are composed mainly of really strong infrastructure folks that are usually very specialized in one particular area. There is a large part of this industry that has never written a script much less knows anything about full-on application development (yes there is a growing group that do). When the infrastructure of tomorrow demands that the infra people are able to take software development methodologies and apply them to network engineering, these folks will need to adapt, or lose their edge. Articles like [this one](http://www.theregister.co.uk/2013/05/24/network_configuration_automation/)  are way off the mark by making statements like all network engineers will lose their jobs, which of course, is preposterous. However it is true that the times are changing, and those that don't change with it will encounter some issues. How that change presents itself - or more specifically, how quickly - has yet to be seen, but with the rapid pace of development of cool new toys like OpenStack, OpenFlow, OpenDaylight, and Open vSwitch (see a trend there?), I would say it's going to happen sooner rather than later.

The winds of change are blowing - be ready.
