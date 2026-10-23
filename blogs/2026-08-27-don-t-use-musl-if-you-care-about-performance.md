---
title: "Don't use musl if you care about performance"
url: "https://blog.brokk.ai/dont-use-musl-if-you-care-about-performance/"
date: "2026-08-27"
author: "Jonathan Ellis"
feed_url: "https://brokk.ai/blog/rss/"
---
I've spent most of my career working inside the JVM, with a sidebar of Python. So the first time I hit incompatible libc with containerized Bifrost , and GPT suggested musl as the solution, not only did I jump on it, I moved my other Rust projects to musl
