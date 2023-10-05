---
title: AirFlow - Software Development Practice that Works
---

# Airflow

**Software Development Practice that Works**

This project is a work in progress, a philosophy about software development, architecture, and engineering.

*A breath of fresh air*

## Is this Agile?

Yes, this 100% compatible with the [Agile Manifesto](https://agilemanifesto.org/principles.html).

## Is this agile?

Yes, it's that too.

agile [ **aj**-*uh*l, -ahyl ]

*adjective*
1. characterized by quickness, lightness, and ease of movement; nimble
1. quick and well-coordinated in movement

## But Why?

Software developers want to get things done. Management wants things to get done. Users want good software. Investors want good returns. We have the technology.

## What about Waterfall?

Sometimes [Waterfall](https://en.wikipedia.org/wiki/Waterfall_model) is presented as the anti-Agile, a problem in need of rescue.

Those who were shipping software before Agile know it's not a linear cascade, but an iterative cycle of steps from start to delivery. A washing machine with a rotary drum more than a waterfall, or sometimes a spiral that narrows to completion.

Requirements, Specification, Design, Construction, Testing, and User Feedback all have a place in software development, but modern practices allow for more flexible deployment of concerns.

Airflow is the new thing, and it's still fluid motion from start to finish.

## Concepts

- [Semantic integrity](#semantic-integrity)
- [Value attention](#value-attention)
- [It's safe to give time estimates](#its-safe-to-give-time-estimates)
- [You can't predict everything](#you-cant-predict-everything)
- [Stories tell what happened](#stories-tell-what-happened)
- [Arbitrary deadlines are arbitrary](#arbitrary-deadlines-are-arbitrary)
- [Be resilient, not fragile](#be-resilient-not-fragile)
- [Make Things to Throw Away](#make-things-to-throw-away)

### Semantic integrity

A rich lexicon of words already exist to describe these processes. Be cautious of newspeak that redefines well established words.

Agile practices embody agility.

### Value attention

Time is one resource your developers have to spend to achieve results, and attention is another that should not be discounted.

"That meeting could have been a chat thread or an email."

How much time does a 10-minute meeting cost? Too much, and it puts the required attendees in a difficult position of excusing the distraction cost.

Asynchronous communication is often a better tool than scheduled meetings. Leave those meetings for when they are truly necessary, so the audience can give good attention.

### It's safe to give time estimates

You don't need to obfuscate time estimates with story points, velocity formulas, or burndown charts. "This should take three days" is a very reasonable string of words to communicate effectively.

Sometimes estimates are wrong. This is the nature of estimation. If something is happening too slowly or ahead of schedule, it is valuable to know what factors are in effect. Estimation values should budget for uncertainty, but should not be artificially inflated to avoid under-estimation. A better solution for that is to not punish inaccurate estimations, but rather deal with the reported factors.

### You can't predict everything

But you can affect your probability of success and delivery. Report what factors are helping and which ones are slowing things down without waiting for a meeting. Make it easy for management to know what to do.

### Stories tell what happened

Having a task with clear outcomes and a general direction is great, but don't waste time on noisy documentation about the boring parts. Get the thing done, then fill in the details of your report with useful information about what works and what doesn't.

Add to the story as you go after important details emerge, especially factors that are working for or against your efforts. Communicating those factors asynchronously should help management give attention where it's needed.

### Arbitrary deadlines are arbitrary

We have continuous integration and continuous delivery (CI/CD) now. You don't need to wait for multiple two-week cycles to get things done. The planning meeting is scheduled for any time planning needs to happen.

When you sprint, you should be laser-focused on the goal, powered by preparation, and delivering at maximum speed with a clear path forward. This is intense, and sprinters should not be interrupted or distracted while sprinting. When the goal is reached, it is expected that the sprinter take a moment to recover from exhaustion.

If you are constantly in a state of "sprint", that is not sprinting. Sometimes the situation requires a marathon, haul, or brisk jog. *See* [Semantic Integrity](#semantic-integrity)

Deadlines should be meaningful and carefully chosen. As part of [valuing attention](#value-attention), arbitrary deadlines can be stressful and distracting while impacting quality, so consider this cost.

### Be resilient, not fragile

Your processes should be as flexible as your organization, and realistic organizations have technical debt, legacy support, spurious decision-making, employee turnover, vendor contracts, and third party relationships. You shouldn't need a long runway to know if your process is working. Let your team find out what works with a helpful starting path.

### Make things to throw away

This is a whole chapter from [*The Mythical Man-Month*](https://en.wikipedia.org/wiki/The_Mythical_Man-Month#The_pilot_system). Building software involves a great deal of discovery and experimentation. If you're not making mistakes, are you aware of the mistakes you don't know you're making? What about the mistakes you or a coworker could be making? How would you know to recognize failure if you haven't seen it go wrong before?

This discovery and experimentation process doesn't need to have everything documented and tested if it distracts from developer flow state. Write about the interesting moments and create tests for notable behaviors. Sketch notes along the way and compile the report later.

Be careful of the [Big Ball of Mud anti-pattern](https://en.wikipedia.org/wiki/Anti-pattern#Big_ball_of_mud). There is a natural tendency to build unmaintainable software by adding more things on top of what's already there. If you haven't seen it or done it, you will. Learning better design is a matter of study, practice, and experience.

We have Agile now, so make lots of things to throw away while picking the best parts to keep. Ship good things into production. Strive for quality.

## The Triangle of Success

Find a balance of three:

1. Scope
2. Budget
3. Time