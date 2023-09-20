---
title: "DanGen: A danmaku pattern generator for cool visuals"
date: 2023-08-06T17:32:42+05:00
categories: blog
tag: godot
draft: false
---

I'm not a big Touhou guy; my only knowledge of it is through other people around me talking to me about. One of my online friends; a multimedia artist by the name of Febbs, was audibly complaining about the lack of a good danmaku generator in a vc. I was quite bored at the time and was looking for a new project, so I asked him what he wanted and eventually threw together DanGen in a couple days. DanGen is a simple Danmaku pattern generator, it isn't the _most_ customizable generator; it's standout feature is that it can layer multiple patterns on top of each other as well as having custom sprites and sizes for each spiral. Other than that, there's also some niceties like being able to control fire rate in seconds instead of some arbitrary scale. It's written with Godot, and is reasonably performant, though I still want to a little bit more to improve performance.

It's also open source under a BSD-like license (with a reference to THE STRONGEST PUBLIC LICENSE; The license has an optional requirement to add an acknowledgement that "Cirno is the strongest in Gensokyo", I mean if I was gonna go Touhou, might as well go full on right?) You can find the source code here: https://github.com/Gamer-Kold/DanGen.

A couple things more I want to add before I can call this project _fully_ complete.
- I want to add support for saving a pattern file, so you can send patterns to other people and work on it for more than one session
- I want to add support for re ordering shapes
- I want to create some half decent docs
- And finally I want to optimize it a lot more.
