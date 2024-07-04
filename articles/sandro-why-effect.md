---
title: "Why everyone is talking about Effect"
emoji: "🕌"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: []
published: false
---

This week Effect exploded 🤯

Everyone took notice, and everyone is talking about it.

Both 😇

---

# Why Effect in the first place?
In the heat of the discussion the main doubt about Effect remains: **why?**

> The simple answer is: "it allows to easily **create and maintain complex Typescript applications"

Indeed, that's a bit generic to sell the real value of Effect.

That's my take on "why Effect" 👇

## Type safety
It's so awesome when you refactor some code and **the complier guides** you in all the places in your code that you need to update. That's the power of using types.

Examples:

- Adding a new error forces you to handle it in all the places where it's introduced (e.g. [catchTags](https://effect-ts.github.io/effect/effect/Effect.ts.html#catchtags))
- Adding a new services requires you to provide valid implementations where required (i.e. [provide](https://effect-ts.github.io/effect/effect/Effect.ts.html#provide))
- With the [Match](https://effect-ts.github.io/effect/effect/Match.ts.html) module and pattern matching you are required to handle all cases

## Composable
Dependency injection built in allows to write generic and composable apps.

> Define services, and then **swap and compose different implementations**. This makes testing a breeze, and allows to switch between one solution to another in 1 line of code

You are no more dependent on any framework or library. This is a huge plus 🚀

## Best practices

Effect teaches you best practices (regardless of programming language):

The principles that Effect uses and applies force you to better structure and understand your code.

# What will happen

The people who tried Effect and understood the "why" are now all-in on it:

This heat will increase more and more in the upcoming months as more people learn about it and start to share more examples.

The Effect team is also hard at work to provide more app examples and improve the docs:


Meanwhile, you can start from some of the articles I already published about getting started with Effect:


Effect is no more a bet 🔥!


Now it's the time to start looking into it. My suggestion is to try it, see by yourself the problem that it solves, and share what you learn along the path.

I am doing the same 💁🏼‍♂️

See you next 👋