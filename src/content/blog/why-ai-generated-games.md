---
title: "Why I'm Betting on AI-Generated Games"
description: "Something real is happening. Games are about to become a conversational medium."
pubDate: "Feb 17 2026"
---

Last Tuesday I typed: *"A puzzle platformer where gravity rotates every 10 seconds and you play as a maintenance robot inside a collapsing space station."*

Thirty seconds later I was playing it.

The first version was broken. The robot spawned halfway inside a wall. When gravity flipped, the entire map fell apart. But the fourth version? It worked. Not perfectly. The jump arc felt floaty. The win condition was too easy. But it was playable. And more importantly — it felt like *something*.

That was the moment I stopped thinking of AI-generated games as a gimmick.

Something real is happening here.

## Games Never Had Their YouTube Moment

Video had a barrier. Then smartphones crushed it.

Writing had a barrier. Then blogging crushed it.

Games still have a barrier.

Unity, Unreal, Godot — they're powerful. But they assume you want to become a developer. Most people don't. They want to create something and play it immediately.

What if you could just describe a game and be inside it 30 seconds later?

Not a template. Not a reskinned clone. A game that didn't exist before you described it.

That's what I'm building.

## What Granularity Actually Does

[Granularity Games](https://granularitygames.com) takes a prompt and generates:

- Game logic
- Level layout
- Assets
- Rules
- Win conditions
- Basic balancing passes

Then it runs simulations to make sure the game is at least technically winnable.

Three months ago, it couldn't do this. Levels were often impossible. Enemies spawned behind walls. Sometimes the player just fell forever.

I had to add deterministic constraints on top of the LLM reasoning. Hard rules about gravity, reachable surfaces, collision grids. The AI is creative — but physics still needs guardrails.

Right now the games aren't AAA. They're closer to experimental itch.io prototypes. But they're real. And they didn't exist 60 seconds earlier.

That's the shift.

## The Part That Feels Slightly Unhinged

I'm not just building AI-generated games.

I'm building an AI-native *company*.

Most of the repo was written by AI tools. I architect the system, define the constraints, review the output — but I rarely write raw code anymore.

I have an AI assistant named Grit that handles operational tasks. Email triage. Scheduling. Drafts. Coordination. It has commit access. It has inbox access.

That might be irresponsible. I'm still deciding.

But if the product is AI-generated games, the company should reflect that same philosophy: humans set direction, AI executes.

I'm the bottleneck on taste and vision. Everything else is increasingly automated.

## Why Now?

LLMs crossed a threshold.

Not just code generation — but systemic reasoning. They can model rule interactions now.

Combine that with deterministic safety rails and you get something new:

**Playable systems from language.**

This doesn't compete with Elden Ring. It competes with boredom. It competes with the friction between "I have an idea" and "I made something."

That gap is collapsing.

## The Real Goal

In the next 6 months, I don't need investors. I don't need press.

I want 100 people to generate a game and think: *"Wait… I made this?"*

If that happens, we're early but we're right.

If it doesn't, maybe I'm wrong. Maybe this is just my own obsession.

But I can't unsee the trajectory.

Games are about to become a conversational medium. And I want to build the engine that makes that possible.

— Nick
