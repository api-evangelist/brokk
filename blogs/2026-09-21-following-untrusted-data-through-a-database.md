---
title: "Following untrusted data through a database"
url: "https://blog.brokk.ai/following-untrusted-data-through-a-database/"
date: "2026-09-21"
author: "David Baker Effendi"
feed_url: "https://brokk.ai/blog/rss/"
---
A profile field can be stored safely with a parameterized SQL query and still cause stored cross-site scripting (XSS) when it is later inserted into a page without the right output encoding. The same stored value could cause SQL injection if another part of the application concatenates it into
