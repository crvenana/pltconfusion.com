---
layout: post
title: "Celluloid internals and the actor model"
tags: concurrency ruby eventmachine celluloid
comments: true
---

Continuing from previous two posts about [primitives and abstractions](link), and the [reactor pattern](link), in the last part of the series we'll cover handpicked internals of Celluloid and EventMachine, and explain the gist of their ideas.

## The actor mailbox
