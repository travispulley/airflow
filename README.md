# Airflow

**Software Development Practice that Works**

This project is a work in progress, a philosophy about software development, architecture, and engineering.

*A breath of fresh air*

![Pressure Wind Tunnel at Langley Aeronautical Laboratory, 1950](site_files/windtunnel.jpg "Airflow")

## Is this Agile?

Yes, this 100% compatible with the [Manifesto for Agile Software Development](https://agilemanifesto.org/).

This is referred to within as Agile, in proper noun format with a capital A, to specifically mean this software development philosophy.

## Is this agile?

Yes, it's that too.

agile [ **aj**-*uh*l, -ahyl ]

*adjective*
1. characterized by quickness, lightness, and ease of movement; nimble
2. quick and well-coordinated in movement

## But Why?

- Software developers want to get things done
- Management wants things to get done
- Users want good software
- Investors want good returns
- We have the technology
- Because we care about you

## Preface, Warnings, Disclaimers, and Caveats

These ideas are not final answers, and it offers questions to test existing processes in the interest of improvement. There are many ways to solve problems, and real assessments are useful when it comes to knowing what is working or not working. Much is subjective. Because something works or doesn't in one place for someone doesn't mean it will or won't somewhere else for someone else. Context matters.

This is a product of direct experience and research into experiences of software developers, project managers, and business owners.

Authorship and inspiration can be attributed, but this work is intended for wide input either directly or indirectly. Credit and attribution will be given or kept private with proper attention. Contributions are welcome.

Links are provided to be useful or interesting, but no association is implied.

This is not intended to sow discord with any existing processes or parties who operate them, and no one is accused of being wrong. This is a philosophically rhetorical question of "is this working?" by following the flow of activity, seeing where effort and resources are applied.

Opinions presented are subject to growth and change. There are assertions and generous use of the word "should", but please take with a grain of salt. Thank you.

## Contents

- [What about Waterfall?](#what-about-waterfall)
- [Concepts](#concepts)
- [The Triangle of Success](#the-triangle-of-success)
- [Framework Examples](#framework-examples)

## What about Waterfall?

Sometimes [Waterfall](https://en.wikipedia.org/wiki/Waterfall_model) is presented as the anti-Agile, a problem in need of rescue.

Those who were shipping software before Agile know it's not a linear cascade, but an iterative cycle of steps from start to delivery. A washing machine with a rotary drum more than a waterfall, or sometimes a spiral that narrows to completion.

Requirements, Specification, Design, Construction, Testing, and User Feedback all have a place in software development, but modern practices allow for more flexible deployment of concerns.

Airflow is the new thing, and it's still fluid motion from start to finish.

## Concepts

- [Semantic Integrity](#semantic-integrity)
- [Value attention](#value-attention)
  - [Messaging](#messaging)
  - [Meetings](#meetings)
- [Build trust](#build-trust)
  - [Accountability](#accountability)
- [Data Driven](#data-driven)
- [Give time estimates freely](#give-time-estimates-freely)
- [You can't predict everything](#you-cant-predict-everything)
- [Stories tell what happened](#stories-tell-what-happened)
- [Arbitrary deadlines are arbitrary](#arbitrary-deadlines-are-arbitrary)
- [Be resilient, not fragile](#be-resilient-not-fragile)
- [Make things to throw away](#make-things-to-throw-away)

### Semantic Integrity

A rich lexicon of words already exists to describe these processes. Be cautious of newspeak that redefines well established words.

Agile practices embody agility.

### Value attention

Time is one resource developers have to spend to achieve results, and attention is another that should not be discounted. Being agile means readiness to adapt to change, and this is a valuable resource not to be squandered on poor practices. Find attention in ways that are not expected to be tuned out.

#### Messaging

It's considerate to check if the timing is good for getting a person's attention.

When you need something, give some helpful information up front to help the contact budget enough attention resourcefully. This is covered in detail at [no hello](https://nohello.net/), but for example:

> **Suboptimal:** "Hi.", "Hey can you help me with something?", "Can you call me?"
> 
> **Better:** "I'm getting an error message I don't understand", "Did that job complete yet or have an ETA?", "Care to pair up on this thing I'm working on?"

The same concept applies to emails and documentation. It helps to get to the point quickly.

#### Meetings

"That meeting could have been a chat thread or an email."

How much time does a frequent 10-minute meeting cost? Is it worth the distraction and time for developers to switch context and attention from what they were doing before and after the meeting is scheduled?

Exceptions exist for holding necessary meetings. Do software engineers need to know about [Delta P](https://en.wikipedia.org/wiki/%CE%94P) or the implications of non-redundant sensors for safety? Depending on the application, the answer is a hard yes. Have meetings with mandatory attendance if it's important enough.

Asynchronous communication is often a better tool than scheduled meetings. Leave those meetings for when they are truly necessary, so the audience can give good attention.

With fewer scheduled meetings, more time is available for spontaneous collaboration.

### Build trust

Own mistakes and learn from them, give credit where it's due, and be considerate when directing others' attention. Give people space to make their own mistakes and success, and learn from them. *See* [Make things to throw away](#make-things-to-throw-away)

Put safety cones and caution tape around dangerous parts of the software to protect yourself and others from trouble. A better idea is to build less dangerous software, but that's not always possible or practical. A worse idea is to ignore it as [Someone Else's Problem](https://en.wikipedia.org/wiki/Somebody_else%27s_problem) (S.E.P.).

#### Accountability

Accountability is useful, but consider what that means and how it is applied. The goal is to get things done without bad results, such as project failure or security breaches. Accountability is a tool for taking serious things seriously, but the implicit danger of risking consequences is a powerful force to use sparingly where appropriate.

The risk here is that success can be claimed and failure can be displaced easily within systems that assume correct attribution. Does your system reward honesty in light of unflattering truth?

If accountability is applied to mean satisfying performance goals or metrics, are those goals and metrics meaningful and within the accountable person's control? Consider external factors like delivery vehicles stuck in traffic or waiting for a response. Deferring accountability to someone working with limited or restricted resources needs care and consideration.

Try to motivate accountability with incentives more than danger. Encourage people to jump in front of problems to get them fixed instead of denying them for the sake of appearances.

Beyond risking trust, introducing risk of punishment can be very distracting, while reward for useful action is motivating and valuable. *See* [Value attention](#value-attention)

### Data Driven

Businesses and organizations operate on measurable results. Complexity and nuance of operations, particularly developer activity, can be difficult to measure objectively. Some jobs are clear cut, others more chaotic, and so coming up with meaningful measurements of value that are useful within operations is important to have correct.

That's easy enough to say, but what's the answer then? Many efforts and attempts at measuring things with scalar values have been tried:

- Lines of code
- Point systems
- Pull Requests
- Cans of soda consumed
- Time spent
- Tickets resolved

How well and if any of those work can vary greatly depending on many things, so as usual it's important to factor in context. Those examples can be measured as scalar values, but categorical data like factors working for or against efforts are important too. Categorical data can be accompanied by scalar values too, why not? Examples:

- Great documentation (+5)
- Black box design cost a lot of testing (-3)
- Undocumented bugs discovered (-10)
- Responsive teamwork (+3)
- Useful error messages (+1)

This area will be revisited with updates, in pursuit of better answers here.

Mapping human effort to tangible results is no easy task, though it's important to realize the power of modern software processes and how greatly human efforts can be amplified.

### Give time estimates freely

You don't need to obfuscate time estimates with story points, velocity formulas, or burndown charts. "This should take three days" is a very reasonable string of words to communicate effectively. Update the estimate as new information comes to light.

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

With Agile practices, an urgent situation needing swift response is better served by "yes" than "wait for the meeting". How fast can a bug fix go from incident report to deployment?

### Be resilient, not fragile

Your processes should be as flexible as your organization, and realistic organizations have technical debt, legacy support, spurious decision-making, employee turnover, vendor contracts, and third party relationships. You shouldn't need a long runway to know if your process is working. Let your team find out what works with a helpful starting path.

Human systems with designated roles should allow for those roles to be serviced by different people interchangeably, at least to some extent if not fully. Your software systems have redundancy and flexibility, and your human systems can benefit from those design elements too.

Requiring more roles than can be individually staffed will require one person to perform multiple roles, which can work if there is enough attention budgeted for them to serve those roles effectively. When that goes wrong, attention is at a deficit and the motions of those roles might be done without purpose or awareness. *See* [Value attention](#value-attention)

Specialization is useful and important, but be careful of "not my job" responses to matters of importance that should be shared among teams and individuals within an organization, such as quality and security.

Someone working on an unrelated task should be allowed and encouraged to raise awareness of concerns noticed in the course of normal work. This promotes resilience and should cost little in time and attention. Management should have a playbook for taking alerts to the satisfaction of the reporter.

### Make things to throw away

This is a whole chapter from [*The Mythical Man-Month*](https://en.wikipedia.org/wiki/The_Mythical_Man-Month#The_pilot_system). Building software involves a great deal of discovery and experimentation. If you're not making mistakes, are you aware of the mistakes you don't know you're making? What about the mistakes you or a coworker could be making? How would you know to recognize failure if you haven't seen it go wrong before?

This discovery and experimentation process doesn't need to have everything documented and tested if it distracts from developer flow state. Write about the interesting moments and create tests for notable behaviors. Sketch notes along the way and compile the report later.

Be careful of the [Big Ball of Mud anti-pattern](https://en.wikipedia.org/wiki/Anti-pattern#Big_ball_of_mud). There is a natural tendency to build unmaintainable software by adding more things on top of what's already there. If you haven't seen it or done it, you will. Learning better design is a matter of study, practice, and experience.

We have Agile now, so make lots of things to throw away while picking the best parts to keep. Ship good things into production. Strive for quality.

## The Triangle of Success

This idea is still being worked out, and the name is a working title.

Find a balance of three:

1. Scope
2. Budget
3. Time

## Framework Examples

Finding processes that support people and interactions over serving the process itself isn't always easy. As always with context being important, processes that work in one place may work differently in another place, even within organizations.

Agile practices themselves can be agile, scaling to fit demand and leveraging modularity.

This space will serve examples and components that can be used or modified to suit how teams work.
