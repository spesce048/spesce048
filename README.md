# Samantha Pesce

**Product leader exploring what happens when product people can build, automate and operate with AI.**

I’m a digital product leader with experience across marketplaces, growth and 0→1 products.

More recently, I’ve been spending a lot of time building.

Not because I’m trying to become a software engineer, but because AI-assisted development is changing how much distance there needs to be between identifying a problem and creating something that solves it.

This GitHub is where I document that exploration: automations, agents, prototypes and experiments with connected AI tools.

## What I’ve been building

### 🏋️ Automated Gym Class Booker

A working automation built around a very real problem: the classes I want often open for booking while I’m commuting and unable to grab them manually.

Built with **TypeScript, Playwright and GitHub Actions**, it:

* authenticates with a live booking platform
* identifies configured classes and release times
* books automatically when places become available
* joins waitlists when appropriate
* handles states such as classes not yet being released
* verifies the resulting booking state
* runs on a schedule without requiring me to be there

What started as a small automation became an exercise in production thinking: authentication, state handling, failure modes, scheduling, retries, safe testing and debugging behaviour against a live system.

*The source repository is currently private while the automation is in active use.*

### 🚆 Rail Delay Repay Tracker

An ongoing experiment in turning a recurring bit of personal admin into a data workflow.

The goal is to combine my planned journeys with actual train running data, identify journeys that may qualify for Delay Repay and maintain a record of potential claims.

The interesting problem here isn’t simply scraping a timetable. It’s designing something that can cope with real behaviour: changing travel days, one-off journeys, different train choices and imperfect transport data.

I’m exploring how much of the process can move from **“remember to check this”** to **“surface the exception that needs my attention.”**

### 🎙️ AI Meeting Note Taker

Currently exploring a local meeting assistant using **Codex**.

The aim is for it to:

* listen to meetings
* create transcripts
* distinguish contributors
* learn recurring terminology
* generate useful post-meeting summaries
* save those outputs into a local workspace automatically

I’m particularly interested in how a relatively simple agent can accumulate enough context about a team and its vocabulary to become genuinely useful rather than producing generic meeting notes.

### 🎵 Festival → Spotify workflow

An experiment using connected AI tools to turn festival line-ups and artist setlists into usable Spotify playlists.

The playlist itself wasn’t really the point.

What interested me was moving beyond:

**human asks AI → AI returns text**

towards:

**human defines intent → AI researches → structures information → interacts with another product → produces the outcome**

That distinction is increasingly central to what I’m exploring.

### 🤖 Connected AI workflows

I’ve also been experimenting with AI systems that can work across tools rather than treating the chat window as the end product.

That includes workflows involving things like:

* Spotify
* GitHub
* Google Calendar
* Google Sheets
* Notion
* local files and applications
* browser automation
* scheduled tasks

I’m interested in where these systems are reliable enough to take actions autonomously, where human approval still belongs in the loop, and how you design the boundary between the two.

## What I’m exploring now

**Agentic product experiences**
What changes when software can reason about intent and take actions rather than simply exposing features?

**AI-assisted product development**
Using tools such as ChatGPT, Claude and Codex to move from an idea to working software much faster.

**Personal automation**
Small, highly specific systems that remove recurring admin or solve problems traditional software would never economically address.

**Human-in-the-loop systems**
Understanding which decisions should be automated and which should be surfaced back to a person.

**Context and memory**
How agents become more useful when they understand terminology, preferences, previous decisions and ongoing work.

**Product people who build**
How the role of a PM changes when prototyping can increasingly mean building the real thing.

## The bigger question

The part I find most interesting isn’t whether AI can write code.

It’s what happens to product development when the cost of turning an idea into functioning software collapses.

A product person can increasingly identify a problem, interrogate it, design the behaviour, build an implementation, test it against the real world and iterate without handing every stage to a different discipline.

That doesn’t remove the need for engineering or design.

But it does change what an individual product person can explore before needing them.

That’s the shift I’m trying to understand by building things rather than just reading about it.

## About me

I’m a UK-based product leader working across digital products, marketplaces, growth and 0→1 development.

My professional work is primarily product leadership rather than software engineering, so most of what appears here is deliberately experimental.

Some projects will become polished. Some will probably remain slightly ridiculous automations solving problems that affect approximately one person.

Both are useful.

---

*Currently learning by building, breaking things, debugging them and occasionally discovering I’ve accidentally created infrastructure for a problem that could have been solved with a reminder.*
