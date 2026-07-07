---
layout: post
author: Simon Verhoeven
title: "Book review: The Coding Dojo Handbook"
subTitle: "A practical guide to deliberate practice for developers"
date: 2026-07-07
desc: >
  A review of Emily Bache’s classic handbook on setting up a Coding Dojo. Practical advice on fostering collaborative learning, master-level code katas, and getting development teams comfortable with Test-Driven Development (TDD).
bigimg:
  url: coding-dojo-big.png
  origin: Midjourney
  prompt: "minimalist vector illustration of a modern software engineering dojo, clean lines, programmer collaboration, tech workspace, deep navy blue and bright teal accents --ar 4:1"
img:
  url: coding-dojo-sm.png
  origin: Midjourney
  prompt: "stylized software design pattern iconography, overlapping neon loops and code syntax elements, agile engineering theme"
interesting:
  - url: https://leanpub.com/codingdojohandbook
    desc: "Leanpub: The Coding Dojo Handbook by Emily Bache"
  - url: https://codingdojo.org/
    desc: "Coding Dojo Community Practices and Katas"
  - url: https://coding-is-like-cooking.info/
    desc: "Emily Bache's Blog: Coding is Like Cooking"
categories: agile
tags: [tdd, code-katas, software-engineering, team-collaboration, continuous-learning]
---

# Review: The Coding Dojo Handbook by Emily Bache

Reading Emily Bache’s *The Coding Dojo Handbook* was a welcome reminder of how we actually learn to build software. Most engineering books focus on what framework to use or how the latest language syntax looks, but this one tackles how you actually change team habits. Specifically, how do we help a team of developers get better at their craft when the daily sprint pressure never lets up?

<!--more-->

## Contents

- [The Practice Deficit](#the-practice-deficit)
- [Dojo Formats in Anger](#dojo-formats-in-anger)
- [The Fine Print](#the-fine-print)
- [The Kata in Practice: Shaking Up Old Habits](#the-kata-in-practice-shaking-up-old-habits)
- [The Facilitation Burden](#the-facilitation-burden)
- [Final Thoughts](#final-thoughts)

<!--block1-->

## The Practice Deficit

We have a bizarre habit in software engineering. We expect people to learn new skills, like Test-Driven Development or complex refactoring patterns, while they are writing production code on a tight deadline. It is the equivalent of asking a musician to learn a difficult concerto for the first time while standing on stage at the Royal Albert Hall.

Bache argues for the coding dojo as a structured environment to fix this gap. The core idea is deliberate practice: you take a small, isolated problem (a kata), remove the pressure of shipping to production, and focus purely on the mechanics of writing clean code. For anyone tasked with technical coaching or raising the engineering bar in an organisation, this premise makes complete sense.

## Dojo Formats in Anger

The book shines when it breaks down the actual mechanics of running a session. Bache does not just say, "get in a room and code." She outlines specific formats, mostly Randori and Prepared Kata, and explains exactly how to run them.

In a Randori session, one pair is at the keyboard, switching out every few minutes, while the rest of the room watches and guides. If you have ever tried this with a group of cynical senior developers, you know it can go off the rails quickly. The book provides sensible constraints to stop the session degenerating into a shouting match over code formatting or tabs versus spaces. It focuses on short cycles, small steps, and keeping everyone engaged.

## The Fine Print

Calling this a blueprint is fair, but it comes with strings attached. A coding dojo is not a plug-and-play solution that fixes engineering culture by its mere existence.

First, it demands a recurring, non-negotiable calendar slot. One-off sessions rarely create lasting change. If leadership does not protect regular practice time, perhaps two hours every second Friday, sprint pressure will usually crowd it out.

Second, you need a baseline of psychological safety. If your team culture involves finger-pointing or intellectual posturing during code reviews, developers will refuse to sit at a keyboard and code live in front of peers. The environment has to allow for mistakes, or the whole exercise turns into anxiety management.

## The Kata in Practice: Shaking Up Old Habits

To see the blueprint value, we have to look at how a simple kata can break bad habits. For example, the classic FizzBuzz kata in Java, but with an added constraint from Bache’s playbook: zero conditional statements allowed. No `if` blocks, no ternary operators.

The initial reaction will likely be silence, followed by the usual complaints that this is unrealistic. But as pairs cycle through the red-green-refactor loop, they will have to reach for alternative patterns. They end up using an enum-based state approach and map lookups to resolve output strings.

The win is not the code itself, which you would never ship to production, but the visible shift in developers. They will realise how automatically reaching for a given solution can be a crutch. That brief moment of clarity is exactly what the dojo format is meant to produce.

## The Facilitation Burden

None of this happens without strong facilitation. The hardest part of a coding dojo is not the code, but rather the human element. We can be a defensive bunch, and live coding is intimidating.

Bache spends a good portion of the handbook on the facilitator’s role, and it is easily the most useful section of the book. She gives practical advice on handling the alpha developer who tries to dictate every line from the back row, encouraging the quiet junior who is terrified of making a typo, and keeping the energy from bottoming out.

Without a facilitator actively protecting the rules and keeping the atmosphere constructive, the dojo quickly turns into a tedious lecture or an argument over syntax.

## Final Thoughts

*The Coding Dojo Handbook* is a slim, pragmatic guide that skips academic theory in favour of real-world application. It is an excellent resource, but the mechanics are only half the battle.

If you have management backing to protect the time, the patience to facilitate sessions properly, and a team that trusts each other enough to fail in public, this book gives you the tools to meaningfully change how your team writes code.
