---
title: "Kotlin Flow"
ring: adopt
quadrant: Android
tags: [Android, Kotlin]
---

<p>Flows in Kotlin are asynchronous data streams that emit values sequentially. They are built on top of coroutines and can be used to represent data from various sources, such as network calls, databases, or events.</p>

<h2>Creating flows</h2>

<p>Flows are created using the flow() function. This function takes as input a block of suspendable code which emits the flow values.</p>
