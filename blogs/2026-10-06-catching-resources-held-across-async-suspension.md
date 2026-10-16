---
title: "Catching Resources Held Across Async Suspension"
url: "https://blog.brokk.ai/catching-resources-held-across-async-suspension/"
date: "2026-10-06"
author: "David Baker Effendi"
feed_url: "https://brokk.ai/blog/rss/"
---
An asynchronous function can release every resource before it finishes and still hold one at the wrong time. Borrow a connection from a small pool, then wait for an unrelated network request, and that connection remains occupied while the function is paused. A release call later in the function does
