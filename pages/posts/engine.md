---
title: Working on a game engine
date: 2022/12/15
description: A game engine for development in Rust.
tag: Game development
author: TeaSpillStudios
---

## What is working on a game engine solo like?
It can lead to interesting situations where a problem can continue for days. For example, one problem I faced was trying to get MiniQuad (a rendering solution) to work with my engine. I needed ownership of the `world` variable in two places, `Stage` and `Engine`. `Stage` was for MiniQuad as it required a separate struct and `Engine` was for my engine. In the end, after a week of trying to solve it I ended up rewriting the engine. It turned out to be a good idea and the engine is now called [Taconite](https://github.com/TeaSpillStudios/Taconite). Within the week I had a new engine set up and it had more capability than my old engine did at 325% faster compile times and a whole lot more control over the engine.

## Issues
The biggest issue with writing a game engine solo is if there is an issue there are not many people that can help you solve the issue. However, it can sometimes be fun to solve challenges by yourself, especially when they are complicated like they can be in a game engine.
