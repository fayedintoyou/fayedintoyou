# Hi, I’m Faye

I’m a product engineer working across platform engineering, distributed systems, and increasingly the developer experience around agentic software engineering.

I'm a bit of a late bloomer when it comes to software development. Computers and the internet have always been a huge part of my life, but when I first started undergrad I pursued a different direction first. I studied economics and international relations at JMU, including several years of Arabic (الفصحى — which, as it turns out, is not especially helpful for everyday conversation, lol).

I lucked into a job in federal R&D after college and got started in systems engineering, helping federal agencies think about software standardization and shared processes/procedures. A few years in, I decided I really _did_ like computers, and pursued another bachelor's in computer science at Oregon State alongside my dayjob.

That background is probably why I tend to approach technical systems through a broader lens: incentives, organizations, users, and all the weird reasons systems end up working differently in practice than they do on paper.

In summation, I've spent the last nine years of my professional life across federal R&D and national security at MITRE, and regulated fintech and platform engineering at Capital One.

Most of my software career has happened in private, locked away in internal repositories and company systems, but I've decided to change that. I want to build more in public, write down more of what I’m learning, and leave behind artifacts that can be more broadly useful (and perhas more improtantly, more broadly scrutinized). 

Lately I’ve been especially interested in agentic systems (especially within preexisting enterprise systems & bureacracies), and that has shaped a lot of the work I’ve been doing internally at Capital One: how much the structure around the model actually helps, what should be left to the model versus an accompanying harness, and how to build patterns that don’t become obsolete six months later given the pace of model improvement.

## Context Kit

I’m currently building [Context Kit](https://github.com/fayedintoyou/context-kit), a Git-backed way to give agents durable context and working methods across projects.

It grew out of lessons from my own personal development workflows, experiments at work, and patterns I’ve seen from other people building agentic systems.

The basic idea is that useful context should be inspectable, reviewable, and able to evolve alongside the work. Rather than treating context as one enormous prompt, an opaque retrieval layer, or a pile of ever-growing skills, Context Kit organizes it into small, navigable hubs that agents can progressively browse and read as needed.

The same system can carry working methods, skills, specifications, provenance, trust, and freshness signals without turning them into hidden state.

It’s also where I’m experimenting with a broader question I keep coming back to: **where is the proper boundary between deterministic actions and opionated (human guided) orchestration, versus what should we leave to ever more powerful models?**

More at [fayelore.com](https://fayelore.com) · [faye@fayelore.com](mailto:faye@fayelore.com)
