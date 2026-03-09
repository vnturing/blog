+++
title = 'Code is still a liability'
description = 'The more code your team produces, the more code your team must maintai.'
date = 2026-03-09
tags = [ "technology", "AI", "software development", ]
draft = false
readTime = true
+++

Experienced engineers understand the virtues of writing less code. Many of you have probably heard the phrase, *"code is a liability"*. With new AI tools -- tools that can produce thousands of lines of code in seconds -- the idea is more important than ever. It tells a story about how software actually behaves over time.

To understand it, we must distinguish between two things that are often confused: **value** and **implementation**.

One thing I have been told over and over again is that my job is not to write code, but produce working solutions. Users care about outcomes, not code. The codebase is simply the machinery that produces those outcomes.

That distinction matters because code carries a hidden cost. Every line of code is something that must be understood, maintained, tested, secured, and eventually, rewritten. Code is not a static artifact like a shoe or a chair. It lives inside an ecosystem of changing dependencies, evolving business requirements, and shifting hardware environments. What works today becomes technical debt tomorrow.

That's why experienced engineers recognise that **every line of code is a long-term obligation**.

> "Measuring programming progress by lines of code is like measuring aircraft building progress by weight." - Bill Gates

This joke works because the metric is backwards. In engineering, heavier aircraft are not necessarily better aircraft. Similarly, larger codebases are rarely better systems. More code usually means more bugs, more complexity, and a greater surface area for things to break.

There is a [famous story](https://web.archive.org/web/20121230102122/http:/folklore.org/StoryView.py?project=Macintosh&story=Negative_2000_Lines_Of_Code.txt&sub=HN0) from early Apple development that illustrates this point. According to Andy Hertzfeld, during work on the QuickDraw graphics system, engineer Bill Atkinson optimized the region calculation machinery with an algorithm that was both simpler and more general. The rewrite made the software significantly faster, but also removed roughly 2000 lines of code. When it came time to report his weekly lines of code (LoC) count to management, he reportedly submitted *-2000*.

Deleting code was the improvement.

This instinct is not unique to programming. Writers have been saying something similar for generations.

Willian Zinsser, author of *On Writing Well*, argued that good writing comes from subtraction. Clutter hides meaning. Strong prose emerges when unnecessary words disappear.

This reduction is not merely cosmetic. It materially improves reliability.

## Features as Code

Now here is the part that often goes unsaid: **features are code**.

It might sound obvious, but the implications are underappreciated. When a team ships a new feature, they don't just deliver a capability. They also take on an obligation. Every feature requires code to exist and, as we have already established, *with great code, comes great responsibility*.

That's why experienced product teams are not just sceptical of bad features. They are sceptical of *unnecessary features*. Even good ones. Because every feature added is weight the system must carry forward. It increases the cost of every future change. The larger a codebase becomes, the more inertia it develops.

## The AI Factor

The AI era amplifies this problem.

Generative tools have dramatically reduced the effort required to produce code. Features that would take days can be scaffolded in minutes. That power is undeniably useful, but it also removes the one friction that historically kept feature bloat in check.

When building something was hard, that difficulty acted as a natural filter. Teams had to prioritise, because engineering time was finite and expensive. Not every feature made the cut. The cost of implementation forced a conversation about value.

Now that conversation is much easier to skip.

> "When you *can do anything*, how do you choose what’s *worth doing*?" - Tawanda Munongo, [AI and the Devaluation of Effort](https://tawandamunongo.dev/posts/2025/10/ai-devaluation-effort/#:~:text=When%20you%20can%20do%20anything%2C%20how%20do%20you%20choose%20what%E2%80%99s%20worth%20doing%3F)

If an AI-assisted engineer can generate a feature in an afternoon, the temptation is to ship it. Why not? The effort to build it is almost zero. Yet, the true cost of software isn't in writing it. The expensive part is **owning it for the next five or ten years**.

The cost has not fallen. If anything, it has grown. Because now there is simply more code in the world.

The result is a new class of bloated software -- applications stuffed with features that were cheap to ship. Not because AI wrote bad code, but because the teams using it stopped asking whether the feature was worth owning -- only whether it was cheap to build.

### Conclusion

The lesson from the most experienced voices in software is not to slow down in the age of AI. It's to keep asking the question that cheap code makes easy to forget:

Not *can we build this?*

But *should we own this?*

Because features are code. And code is still a liability.